# replace-script
    -> Recursively looks through a given path to find and replace a given string pattern with a new one
    -> Usage: ./replace path oldpattern newpattern
    -> path is the directory or file that the user wants to cycle through
    -> oldpattern is the string that will be replaced
    -> newpattern is the string that will replace oldpattern

# run-test
    -> Creates a directory named 'test' containing other directories and files that can be used to test replace-script
    -> Usage: ./run-test setup|teardown
    -> setup creates the 'test' directory and its contents
    -> teardown removes the directories and files within 'test'
