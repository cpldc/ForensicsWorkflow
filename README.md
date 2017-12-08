# ForensicsWorkflow
Workflow documents for CPLDC Digital Forensics 

exifscript:
	Runs exiftool on . and outputs as csv to .
	Should be copied to $PATH

CopyGoodFiles
	asks for collection name ($collName)
	makes directory in ~/Documents with that name ($collName)
	copies files from ./ToBeCopied.txt to ~/Documents/$collName
	
workflow.txt:
	Describes process in detail

JoeCopy: 
	rsync -av from ~/workingdirectory to .

webm-takevid & ffmpeg-shorten: 
	just screencap scripts

