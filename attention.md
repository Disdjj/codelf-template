## Language: {language}
> Analyze whether the current project has incorporated language-standardization tools, such as modular structure, precompiled languages, etc.

**Formatter Library:**
- [tools1 (version)]()
- [tools2 (version)]()

**Usable Utilities and Components:**
> List the directories of existing common methods and components in the current project, along with a brief description of their functions.
```
- pkg // {module name}
	- xxx // {function or component description}
```

**Coding Conventions:**
> Clear separation of code responsibilities: routing, business logic, and utility functions are organized independently.
```
- api    // Request routing management
- views  // Business logic implementation
- utils  // Utility function definitions
...
```

**Folder and Variable Naming Conventions:**
- Semantic naming
- camelCase or kebab-case
- Reasonable length constraints

**Error Monitoring and Logging:**
> Make proper use of `debugger`, `console`, and other debugging statements, ensuring their removal before production.
> Add appropriate comments to enhance readability, but avoid excessive annotation.