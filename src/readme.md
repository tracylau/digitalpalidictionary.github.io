View the file in browser

`mdbook watch -o`

Make edits, commit and push to ’source’ branch.

`git add -A`
`git commit -m upd`
`git push origin source`

Build the HTML from ’source’, enter ./book folder, commit and push to ’main’ branch.

`./build.sh`
`cd book`
`git add -A`
`git commit -m upd`
`git push origin main`
`cd ..`
