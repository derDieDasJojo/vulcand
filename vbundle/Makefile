test: clean
	go test -v ./ -cover

cover: clean
	go test -v ./ -coverprofile=/tmp/coverage.out
	go tool cover -html=/tmp/coverage.out

clean:
	find . -name flymake_* -delete

sloccount:
	 find . -name "*.go" -print0 | xargs -0 wc -l

install: clean
<<<<<<< HEAD
	go install github.com/vulcand/vulcand/vbundle
=======
	go install github.com/derDieDasJojo/vulcand/vbundle
>>>>>>> 5c53229d7b95e1acfbd8b664b556e99730115c32
