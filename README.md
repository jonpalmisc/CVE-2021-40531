# CVE-2021-40531

![Exploit Demo](https://jonpalmisc.com/assets/img/cve-2021-40531/demo.gif)

> This proof-of-concept in action.

[Sketch](https://www.sketch.com) is a popular UI/UX design app for macOS. This
post covers a vulnerability in Sketch that I discovered back in July,
CVE-2021-40531. In its simplest form, it is a macOS quarantine bypass, but in
context it can be used for remote code execution.

For more details, see my [blog post](https://jonpalmisc.com/2021/11/22/cve-2021-40531)
for a complete writeup.

## Notes

If you are testing this proof-of-concept locally, be aware that `feed.rss`
expects your web server to be running on port 8080.
