# test-gitjournal
Trying to understand how GitJournal might be used as a general git client.

I haven't been impressed with the "git clients for android", and I often like to play with programming ideas when I'm out and about. 

## Steps to set it up (I think)
1. Create repo
2. In GitJournal: Add Repository
3. In GitJournal: Setup Git Host (manual)
4. In GitJournal: Settings -> Storage & File Formats -> Store Repo Externally -> Select folder under "Documents"

## Test that it can pick up on external .md files 
1. In Files app: duplicate an existing file
2. Open GitJournal. Is the file shown?

**no**

3. Create a new note in GitJournal. Does our duplicated file get included?

**[New note shows up](https://github.com/tedbrandston/test-gitjournal/commit/6459cb0390f5916999c9aa81d28617aaf8357dff), but not duplicated one.**
