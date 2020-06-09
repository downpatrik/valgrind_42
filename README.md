# valgrind_42

brew update
brew install valgrind
alias valgrind="~/.brew/bin/valgrind"

valgrind --tool=memcheck --leak-check=full ./your_project
