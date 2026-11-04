## Description
Include a summary of the changes and the related issue. Include relevant context.

Fixes `# (issue)`

## Type of change
- [ ] Improvement (improve upon an existing feature)
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Chore or Refactor

## Cross-Repository Impact
- [ ] Requires changes in `ReportsPlusPluginWeb` (C#)
- [ ] Requires changes in `ReportsPlusWebApplication` (Java)

## Checklist:
### **ReportsPlusWebApplication:**
- [ ] Builds Clean
- [ ] Updated applicationVersion String in `StaticStrings`
- [ ] Assign _'-dev'_ Tag if Version is a Development Version
- [ ] Update `pom.xml` version
- [ ] Update `electron/package.json` version
- [ ] Update `patch_notes` File with **date of release** and **version number**
### **ReportsPlusPluginWeb:**
- [ ] Update Plugin Assembly Version
- [ ] Update Plugin Config Version in `ReportsPlusSettings`
