## running main command
go run main.go -h

## running helloworld
go run main.go helloworld


# Build and run
go build -o helloworld
./helloworld -d
 ./helloworld


 # important links
 https://github.com/spf13/cobra
 https://www.youtube.com/watch?v=IOVBSVox1lM


### to package dependency in source code run
 go mod vendor

###  build options
https://goreleaser.com/customization/build/?h=builds

# For releasing a new version

tag `git tag -a v0.1 -m "locu test cli"`
Push `git push origin v0.1`

### used following video for bootstraping 
https://www.youtube.com/watch?v=IOVBSVox1lM
