**This project is done as part of Computer Networks course**

To run the code, the files `server.py` and `client.py` have to be moved to 2 different locations and they have to be invoked seperately as `python server.py $portnumber$` and `python client.py $portnumber$`. Note that same portnumber has to be provided while invoking the 2 scripts

Commands supported
- `IndexGet shortlist starttimestamp endtimestamp`
   - Returns _name_,_size_,_type_ of each file changed in between these times
- `IndexGet longlist`
   - Returns _name_,_size_,_type_ of each file 
- `FileHash verify <filename>`
   - Returns ​checksum and last​ modified timestamp of the input file.
- `FileHash  checkall`
   - filename,   checksum   and   last​ modified   timestamp   of   all  the files in the shared directory
- `FileDownload <filename>`
   - Downloads the file in the server directory to the client directory
- `help`
   - Displays list of available commands

