# beam-go
## Steps to go the program 
1. First use this link to download the Golang (https://go.dev/dl/)

2. Check in the environment variables to see whether this '''go1.18.windows-amd64.msi''' is installed or not.

3. Then in documents create a new folder with name beam-go in 44517.

4. Also create a repo in the github with the name beam-go.

5. Open gitbash from beam-go folder and give the follwing commands

>go mod init github.com/<yourgithubusername>/beam-go(give your github user name in place of yourgithubusername)
  
>go get -u github.com/apache/beam/sdks/v2/go/pkg/beam

>go install github.com/apache/beam/sdks/v2/go/examples/wordcount 
 
>wordcount --input <PATH_TO_INPUT_FILE> --output counts (give your input file name in place of <PATH_TO_INPUT_FILE> to generate the output)

