# Documentation Repository (Wiki)

This is a Chinese technical documentation repository that primarily uses GitHub's Wiki feature for content management. The main repository contains minimal files and serves as a gateway to the Wiki documentation.

Always reference these instructions first and fallback to search or bash commands only when you encounter unexpected information that does not match the info here.

## Repository Nature
- **Type**: Documentation-only repository
- **Primary Content Location**: GitHub Wiki tab (not in repository files)
- **Language**: Primarily Chinese
- **Build Requirements**: None - no compilation or build processes needed
- **Dependencies**: None - no package managers or dependency files

## Working Effectively

### Initial Setup
- Clone the repository: `git clone https://github.com/wudanyang27/wiki.git`
- Navigate to directory: `cd wiki`
- No additional setup steps required - there are no dependencies to install

### Repository Structure
```
.
├── .git/                    # Git version control
├── .github/                 # GitHub configuration
│   └── copilot-instructions.md
└── readme.md               # Basic repository description (Chinese)
```

### Key Commands That Always Work
- `git status` - Check repository status
- `git pull origin main` - Pull latest changes
- `git add .` - Stage all changes
- `git commit -m "message"` - Commit changes
- `git push origin [branch-name]` - Push changes

### Commands That Don't Apply
- No build commands (no `npm install`, `make`, `mvn`, etc.)
- No test commands (no `npm test`, `pytest`, etc.)
- No dependency installation
- No compilation steps
- No deployment processes

## Working with Documentation

### Main Documentation Access
- **Primary Method**: Navigate to the Wiki tab on GitHub web interface
- **URL Pattern**: `https://github.com/wudanyang27/wiki/wiki`
- All technical documentation is maintained in the Wiki, not in repository files

### Repository File Changes
- Changes to `readme.md` should maintain Chinese language consistency
- Keep repository structure minimal - avoid adding unnecessary files
- Focus on repository-level information, not technical documentation content

### Git Workflow
- Always check current branch: `git branch`
- Create feature branches for changes: `git checkout -b feature/description`
- Make small, focused commits
- Use descriptive commit messages in English or Chinese as appropriate

## Validation Steps

### After Making Repository Changes
- Verify file encoding is UTF-8: `file -i readme.md`
- Check git status is clean: `git status`
- Verify Chinese characters display correctly: `cat readme.md`
- Test that files can be viewed properly on GitHub web interface

### Documentation Validation
- Access Wiki tab in browser to verify documentation is accessible
- Check that Wiki pages render correctly
- Verify internal Wiki links work properly
- Ensure Chinese characters display correctly in Wiki pages

### Pre-commit Validation
- Run `git diff` to review changes before committing
- Ensure no unintended files are staged: `git status`
- Verify commit message is clear and descriptive

## Common Tasks

### Repository Maintenance
- Keep `readme.md` updated with current repository purpose
- Maintain `.github/` directory for repository configuration
- Update copilot-instructions.md when repository purpose changes

### Documentation Updates
- Use GitHub Wiki web interface for content changes
- Maintain Chinese language consistency in documentation
- Create clear navigation structure in Wiki pages
- Use appropriate markdown formatting

## Time Expectations
- Git operations: Immediate (< 1 second)
- File editing: Immediate
- GitHub Wiki access: 1-2 seconds for page loads
- No build or test times - repository contains no executable code

## Troubleshooting

### Common Issues
- **Chinese character encoding**: Ensure files are saved as UTF-8
- **Wiki access**: Use GitHub web interface, not local files
- **Empty repository feeling**: This is normal - content is in Wiki tab

### What NOT to do
- Do not add build tools or dependency files
- Do not create source code directories
- Do not add CI/CD pipelines for code building
- Do not search for package.json, Makefile, or similar build files

## Repository Context
This repository serves as a container for technical documentation stored in GitHub Wiki. The minimal file structure is intentional - the real content lives in the Wiki tab of the GitHub repository.

### Quick Reference Commands
```bash
# Basic workflow
git status
git add .
git commit -m "Update documentation references"
git push origin [branch-name]

# File viewing
cat readme.md
ls -la
```

### File Contents Reference

#### readme.md
```
# 技术文档库

这是一个用于存放技术文档的仓库。所有文档均位于 `wiki`  tab 下，请在该tab中查阅或维护相关文档。
```

## Critical Reminders
- **Wiki First**: Primary documentation is in GitHub Wiki, not repository files
- **No Build Process**: This repository requires no compilation, building, or testing
- **Chinese Language**: Maintain language consistency in Chinese documentation
- **Minimal Structure**: Keep repository file structure simple and focused