To remove a submodule you need to:
- git submodule deinit <path_to_submodule>
- git rm <path_to_submodule>
- git commit-m "Removed submodule "
- rm -rf .git/modules/<path_to_submodule>


Source: https://gist.github.com/myusuf3/7f645819ded92bda6677#file-delete_git_submodule-md
