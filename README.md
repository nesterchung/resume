# resume

simple create your resume html from markdown file.

requirement
---

* tidy
* showdown

```
brew install tidy
npm install -g showdown
```

usage
---

```sh
./cv2html resume.md cv/resume.html

# publish eample
aws s3 sync cv/ s3://bucket/ --acl public-read

```
