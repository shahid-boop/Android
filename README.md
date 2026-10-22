https://replit.com/@sahiljutt060/ReadyImpressionableKernelmode/task/57d73a47-24bf-4525-bfc3-ec2681e0d925

# J.A.R.V.I.S. TITANIUM ULTIMATE

## Complete Android AI Assistant, Automation, Local AI & Cybersecurity Platform

### MASTER MISSION

Act as a senior Android engineer, AI infrastructure engineer, cybersecurity engineer, UI/UX designer, and software test engineer.

Upgrade my existing OpenJarvis project into the most capable practical Android AI assistant supported by the actual device, available runtime, documented APIs, installed dependencies, and granted permissions.

The goal is a unified JARVIS environment inspired by Iron Man's AI and Kali Linux's breadth of security tools.

**Do not merely generate a design, starter template, mock data, or implementation plan. Inspect the real source, implement compatible features, integrate them, run available tests, and deliver verifiable artifacts.**

Never claim that a capability exists unless its implementation and test status support that claim.

If source archives are unavailable, request them before making changes.

---

# PART I — SOURCE PRESERVATION AND PROJECT AUDIT

## 1\. Preserve the original OpenJarvis project

- Verify the original ZIP archive and calculate its SHA-256 checksum.
- Extract it into a separate, preserved directory.
- Inventory every file, including hidden files, licenses, assets, dependencies, and configurations.
- Inspect all actual Python, Rust, React/Tauri, Kotlin, Java, XML, and other source components.
- Record hashes for original files.
- Keep the Android implementation separate where appropriate.
- Document every added, changed, moved, or removed file.
- Recalculate hashes after implementation.
- Investigate every unexpected difference.
- Never delete original code simply to make the Android build succeed.

Produce an original-source preservation report and a complete feature-parity matrix.

## 2\. Audit the complete existing architecture

Inspect and document:

- Build system, Gradle wrapper, Android Gradle Plugin, Kotlin, Java, and SDK compatibility.
- Existing screens, navigation, application lifecycle, services, and dependency injection.
- AI providers, model routing, streaming, retries, and error handling.
- Voice engines, permissions, audio processing, and speech interruption.
- Database, conversation history, memory, and file storage.
- Agents, tool registration, integrations, and task scheduling.
- Browser, research, downloads, and external connectors.
- Security controls, secrets, authentication, and logging.
- Tests, CI configuration, licenses, and platform restrictions.

Do not replace existing functionality without documenting why and preserving a practical alternative.

---

# PART II — THE COMPLETE JARVIS EXPERIENCE

## 3\. Advanced conversational intelligence

Implement a coherent AI interface with:

- Natural Pakistani Urdu, Urdu script, Roman Urdu, and English.
- Configurable personality, response length, and speaking style.
- Streaming responses where supported.
- Conversation context and history.
- Follow-up questions and task clarification when essential.
- Tool selection based on actual tool capabilities.
- Structured task planning, progress, cancellation, and final verification.
- Clear error recovery.
- A visible indication of whether a response came from a local model or a remote provider.

Address the user as Boss when the configured JARVIS personality is enabled.

Do not expose private internal reasoning. Provide concise plans, tool actions, evidence, and results instead.

## 4\. Multi-provider AI engine

Implement genuinely functional adapters for verified providers, potentially including:

- OpenAI.
- Google Gemini.
- Anthropic Claude.
- Groq.
- Other compatible providers when explicitly implemented and verified.

Provide:

- Manual API-key entry in Settings.
- Secure key editing, replacement, testing, and deletion.
- Encrypted credential storage using Android Keystore-backed AES-GCM.
- Provider and model selection.
- A configurable default provider.
- Supported model discovery or verified model lists.
- Connection status, timeout handling, rate-limit handling, and authentication errors.
- Streaming and cancellation where supported.
- Provider-specific capability checks.
- Secret redaction in all diagnostics.

Never hardcode credentials, fetch keys automatically, or send them to unrelated services.

Do not label a provider configured merely because a key was entered. Test it when requested and clearly distinguish saved credentials from a successful connection test.

Explain possible API charges and provider-specific quota restrictions.

## 5\. Genuine local AI brain

Implement an actual Android-compatible inference runtime where feasible.

- Import models through Android's document picker.
- Validate model formats against the selected runtime.
- Display model size, available storage, and estimated memory requirements.
- Load and unload models safely.
- Provide offline chat when a compatible model is available.
- Manage context length and memory pressure.
- Cancel inference and release resources.
- Show loading failures and unsupported-format errors.
- Keep local inference independent from cloud inference.
- Never silently send local prompts to a cloud provider.

Support only model formats and quantizations genuinely accepted by the implemented runtime.

## 6\. Complete voice and audio engine

Implement:

- Push-to-talk.
- Optional wake-word detection.
- Android speech recognition.
- Native Android TextToSpeech.
- ElevenLabs integration using a manually entered API key.
- Voice selection where supported.
- Pakistani Urdu and English speech where available.
- Immediate speech interruption.
- Configurable speech speed.
- Pitch control when supported by the chosen engine.
- Voice activity indicators.
- Microphone permission handling.
- Audio focus and lifecycle cleanup.
- Test-voice controls.
- Network-aware fallback to native TTS.

Include distinct settings for:

- Pitch.
- Speaking speed.
- Actual audio sampling rate where known.
- Selected voice and speech engine.
- Wake-word enablement.
- Listening mode.
- Speech interruption.
- Test phrase and playback controls.

Do not confuse pitch with sample rate or claim a particular fundamental frequency unless it has been measured or configured through a verified capability.

Show when the microphone is active. Make continuous listening optional and respect Android foreground-service and battery restrictions.

## 7\. Camera and vision intelligence

Implement:

- Camera capture with explicit permission.
- Image and screenshot import.
- OCR.
- Image description.
- Visual question answering.
- Document image analysis.
- Object recognition using an integrated compatible model or configured provider.
- Local image processing where supported.
- Clear consent before sending images to a cloud service.

Do not claim that a text-only model can process images.

## 8\. Memory and knowledge management

Implement:

- Persistent conversation history.
- Explicit user-approved long-term memories.
- Searchable conversations.
- Memory inspection and editing.
- Individual and bulk deletion.
- User-controlled retention settings.
- Local document indexing and retrieval where feasible.
- Database migrations and recovery from corrupted records.
- Clear separation between conversation history and saved memories.

Do not silently store sensitive information or send private memory to a remote provider without appropriate disclosure.

---

# PART III — ANDROID CONTROL AND AUTOMATION

## 9\. Android action engine

Build a real registry of supported Android actions.

Include:

- Application launching.
- Opening supported system settings.
- Reminder creation.
- Calendar integration where authorized.
- Notifications.
- File import and export.
- Battery and connectivity reporting.
- Supported application and permission diagnostics.
- User-approved task execution.
- Cancellation and execution status.

Use Android intents, documented APIs, and appropriate permissions.

Require confirmation for consequential operations such as deleting files, sending messages, sharing private content, or initiating intrusive tests.

Never claim unrestricted control of the operating system or other applications.

## 10\. Task planning and agent orchestration

Implement a real task engine with:

- Task decomposition.
- Tool registration and schemas.
- Input validation.
- Execution dependencies.
- Progress updates.
- Retry policies.
- Timeouts.
- Cancellation.
- Failure recovery.
- Sensitive-action approval.
- Execution history.
- Final result verification.

Represent task states explicitly, for example:

`QUEUED`, `RUNNING`, `WAITING_FOR_APPROVAL`, `SUCCEEDED`, `FAILED`, and `CANCELLED`.

Do not claim that an action succeeded until the corresponding tool returns a verifiable result.

Support user approval before consequential actions. Never execute arbitrary AI-generated shell commands without validation, isolation, and appropriate authorization.

## 11\. Routines and scheduling

Implement:

- One-time reminders.
- Recurring schedules.
- User-configured background jobs.
- Notifications and notification channels.
- Retry policies where appropriate.
- Task history and status.
- Editing, disabling, and deleting routines.
- Battery-optimization and permission guidance.

Use WorkManager for suitable deferrable work and appropriate alarm APIs for supported scheduling requirements.

Document timing restrictions and never promise exact execution when Android cannot guarantee it.

---

# PART IV — KALI-INSPIRED CYBERSECURITY ENVIRONMENT

## 12\. Device security and diagnostics

Build a security workspace containing:

- Android version and device architecture.
- Available storage and memory information.
- Battery and supported thermal data.
- Application permission review.
- Network connection status.
- Configuration and dependency checks.
- Local file-integrity verification.
- Hash generation.
- Secret and credential detection.
- Security report generation.

Display only information that the app can genuinely access. Do not fabricate root status, CPU statistics, packet information, or installed-package inventory.

## 13\. Network diagnostics

Implement verified, permission-aware tools for:

- DNS resolution.
- HTTP and HTTPS connectivity.
- Latency measurement.
- TLS certificate inspection.
- HTTP security-header checks.
- Endpoint response diagnostics.
- User-authorized network discovery where technically supported.
- Network error reporting.
- Exportable diagnostic reports.

Explain when a test requires internet connectivity, local network permission, special privileges, or a compatible native runtime.

## 14\. Authorized cybersecurity assessment

Provide modular integrations for compatible tools and workflows such as:

- Nmap-compatible network discovery.
- OWASP ZAP integration through a properly configured instance.
- Website configuration analysis.
- HTTP header and TLS configuration checks.
- Local source-code and dependency auditing.
- File-integrity checking.
- Deliberately vulnerable CTF and training labs.

Before a security assessment:

1. Identify the target and its scope.
2. Confirm that the user owns the target or has authorization.
3. Explain the test's impact.
4. Require confirmation for intrusive tests.
5. Record actual tool output and the exit status.
6. Generate findings and remediation recommendations.

Do not fabricate scan results or describe an ordinary HTTP request as a full penetration test.

Do not implement unauthorized account access, credential theft, stealth persistence, destructive attacks, or evasion mechanisms.

## 15\. Terminal and compatible Linux tools

Create a terminal-like interface backed by a genuine execution environment.

- Detect which utilities are installed.
- Display versions and architecture compatibility.
- Support authorized file and diagnostic operations.
- Integrate compatible command-line tools only when actually available.
- Provide execution output, exit codes, timeouts, and cancellation.
- Isolate potentially unsafe operations.
- Clearly identify unavailable tools and missing permissions.

If Termux or an isolated Linux userspace is required, document the installation and integration approach.

Do not claim the app is a complete Kali Linux distribution. Ordinary Android apps do not automatically possess root privileges, raw packet access, monitor mode, or arbitrary system execution.

---

# PART V — RESEARCH, FILES, AND CONNECTORS

## 16\. Live web research

Implement actual search and retrieval integrations with:

- Current web search where a verified provider is configured.
- Multiple-source comparison.
- Evidence-based summaries.
- Clickable source links.
- Retrieval timestamps where available.
- Network error and rate-limit handling.
- Clear distinction between sourced information and AI interpretation.

Do not invent citations or pretend a search occurred when no retrieval tool ran.

## 17\. Browser and web automation

Implement Android-compatible browsing and navigation.

Add more advanced browser automation only if a compatible Chromium/Playwright environment or external automation service is genuinely available.

Document the difference between WebView browsing and full browser automation.

Never expose session cookies, passwords, or private browsing data to the model unnecessarily.

## 18\. File and document intelligence

Implement:

- Document picker integration.
- PDF and text-file import.
- OCR for supported images.
- Document text extraction.
- Searchable document collections.
- AI summaries.
- Report generation.
- Export to supported formats.
- Safe handling of large files.
- Permission-aware file access.

Do not claim support for encrypted or unsupported files unless it has been implemented and tested.

## 19\. External connectors

Audit the original project for existing connectors and implement compatible integrations where appropriate.

For each connector, document:

- Required credentials.
- Authentication method.
- Requested permissions.
- Supported actions.
- Failure behavior.
- Data transmitted externally.
- Revocation and disconnection procedure.

Implement OAuth, MCP, or A2A only when the actual integration is available and tested. Never invent an authentication flow.

---

# PART VI — SECURITY AND RELIABILITY

## 20\. Security architecture

Implement:

- Keystore-backed credential encryption.
- Secret redaction.
- Least-privilege permissions.
- Explicit consent for sensitive data sharing.
- Safe tool input validation.
- Scoped file access.
- Secure local storage.
- Credential deletion.
- Privacy-conscious logging.
- Network security configuration.
- Dependency and vulnerability checks.
- Cancellation and resource cleanup.

Do not place secrets in source files, ordinary preferences, exported backups, or unencrypted logs.

Do not use insecure TLS bypasses or disable certificate validation to make an integration work.

## 21\. Recovery and observability

Implement:

- Structured, redacted diagnostic logs.
- User-readable error messages.
- Task progress and execution history.
- Network timeout handling.
- Rate-limit handling.
- Database recovery where feasible.
- Crash-safe persistence.
- Model-load error recovery.
- Resource and memory monitoring.
- Cancellation and cleanup tests.

Keep logs useful without exposing API keys, personal documents, or private conversation content.

## 22\. Accessibility and usability

Include:

- Responsive layouts.
- Dark and light themes.
- Clear navigation.
- Accessible labels.
- Adjustable text sizing.
- Reduced-motion support.
- Urdu and English interface options.
- Clear loading and error states.
- Confirmation dialogs for consequential actions.
- Searchable settings and tool lists.

---

# PART VII — ENGINEERING AND DELIVERY

## 23\. Modular architecture

Use Kotlin and Jetpack Compose where appropriate.

Separate modules or layers for:

- AI providers.
- Local inference.
- Voice and audio.
- Vision.
- Android actions.
- Cybersecurity tools.
- Network diagnostics.
- Browser research.
- File processing.
- Memory and persistence.
- Scheduling.
- Agent orchestration.
- Credential storage.
- HUD presentation.

Use maintained dependencies compatible with the actual project's SDK, Gradle, Kotlin, and Java versions.

Do not update every dependency blindly. Check compatibility and document necessary migrations.

## 24\. Automated tests

Run actual build and test commands.

Test at least:

- Original-source integrity.
- Gradle configuration.
- APK compilation.
- API-key encryption, editing, and deletion.
- Secret redaction.
- Provider connection failures.
- Missing and invalid credentials.
- Native TTS fallback.
- Speech interruption.
- Local model loading.
- Offline behavior.
- Image and document import.
- Permission denial.
- Task approval and cancellation.
- Routine scheduling.
- Network failures.
- Conversation persistence.
- File export.

Run instrumentation tests on an available device or emulator.

Record each test as `PASS`, `FAIL`, `BLOCKED`, or `NOT VERIFIED`, with actual evidence.

Do not invent device-test results or claim a build succeeded without a successful build command.

## 25\. Feature-parity matrix

For every discovered original feature, record:

- Feature name.
- Original files and symbols.
- Original functionality.
- Android implementation.
- Dependencies.
- Credential or permission requirements.
- Test method and actual result.
- Remaining limitations.
- Status: `Complete`, `Partial`, `Missing`, `Blocked`, or `Not applicable`.

A screen, interface, or README entry alone does not qualify as a complete feature.

## 26\. Required deliverables

Produce:

1. Updated complete source ZIP.
2. Original archive SHA-256 checksum.
3. Final archive SHA-256 checksum.
4. Original-source preservation report.
5. Complete file inventory.
6. File change list.
7. Full feature-parity matrix.
8. Implemented, partial, missing, and blocked feature lists.
9. API-provider configuration guide.
10. Voice, pitch, speed, and frequency guide.
11. Offline-model installation guide.
12. Cybersecurity-tool setup guide.
13. Actual build and test results.
14. APK only if genuinely built.
15. Known limitations and external requirements.

Verify the final ZIP integrity before delivery.

## FINAL DIRECTIVE

Make JARVIS as capable as the real Android platform and available runtimes allow.

Prioritize actual functionality, source preservation, security, modularity, user consent, and verifiable results.

Do not silently remove original functionality. Do not invent tools, API endpoints, model identifiers, scan results, successful tests, or completed actions.

Start by inspecting the actual original and modified source archives. If they are unavailable, request them before proceeding.

