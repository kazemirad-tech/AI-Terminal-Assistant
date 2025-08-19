# Limitations & Risks

This document outlines the known limitations and potential risks associated with **AI-Terminal-Assistant**. Transparency is essential for building trust with users, contributors, and stakeholders.

---

## ⚙️ Functional Limitations

- **No GUI by default**: The assistant operates entirely in terminal environments. A graphical interface is planned but not yet available.
- **Limited context memory**: The assistant does not persist long-term memory across sessions unless explicitly configured.
- **Offline model constraints**: Local execution may limit access to large-scale models or external APIs unless manually integrated.
- **Plugin maturity**: While plugin support exists, the ecosystem is still evolving and may lack stability or documentation.

---

## 🔐 Security Considerations

- **Shell command execution**: Running shell commands from natural language input introduces risk. Sandbox mode and audit logging are recommended for production use.
- **User-defined prompts**: Custom prompt templates can alter assistant behavior in unpredictable ways if not validated.
- **Local file access**: The assistant may interact with local files depending on configuration. Proper permissions and isolation are advised.

---

## 📉 Performance Trade-offs

- **Model size vs. speed**: Lightweight models ensure fast execution but may sacrifice depth or accuracy in complex tasks.
- **Resource usage**: Running locally may consume CPU/RAM depending on model size and task complexity.

---

## 🧪 Experimental Features

- **Prompt engineering layer**: While powerful, this layer is experimental and may produce inconsistent results depending on template quality.
- **Code suggestions**: Inline code generation is context-aware but not guaranteed to be syntactically or semantically correct.

---

## 🚧 Future Improvements

- Enhanced memory and session continuity  
- GUI wrapper for non-technical users  
- Plugin validation and sandboxing  
- Enterprise-grade telemetry (opt-in only)

---

## 📌 Disclaimer

This project is under active development. Users are encouraged to test in isolated environments and report issues. Contributions and feedback are welcome to improve stability, security, and usability.

