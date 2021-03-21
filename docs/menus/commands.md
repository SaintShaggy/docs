
# WWIV Menu Commands
***

Here is the list of all WWIV Menu Commands available in the Menu Editor broken
out by category.

## Category: AutoMessage
***

### amsg:delete
    Deletes the auto message (cosysop required)


### amsg:email
    E-mail the author of the automessage


### amsg:lock
    Locks the automessage (cosysop required)


### amsg:read
    Read the auto message
    [use automessage:read instead]


### amsg:unlock
    Unlocks the automessage (cosysop required)


### amsg:write
    Writes a new auto message


### AutoMessage
    Displays the legacy automessage menu


### ReadAutoMessage
    Read the auto message


## Category: BBSList
***

### bbslist
    Legacy BBSList Menu


### bbslist:add
    Adds a new BBS to the BBSList


### bbslist:bbslist
    Legacy BBSList Menu


### bbslist:delete
    Deletes a new BBS from the BBSList


### bbslist:net
    Read the network bbs lists


### bbslist:read
    Read the bbslist


## Category: Chain
***

### Doors
    Enter the doors, or chains section.  Like '.'


### RunDoor
    <door name>
    Runs a door (chain) with doorname matching, exactly, the description you have
    given the door in //CHEDIT


### RunDoorFree
    <door name>
    Runs a door (chain) with doorname matching, exactly, the description you have
    given the door in //CHEDIT, but this function bypasses the check to see if
    the user is allowed to run the door.


### RunDoorNumber
    <door number>
    Like RunDoor, but you must specify the #1 in //CHEDIT instead of the
    description.


### RunDoorNumberFree
    <door number>
    Like RunDoorFree, but you must specify the #1 in //CHEDIT instead of the
    description.


## Category: Conference
***

### DisableConf
    Turns conferencing off


### DownDirConf
    Go to the prior directory conference '{'


### DownSubConf
    Decrement ({) to the next sub conference


### EnableConf
    Turns conferencing on


### JumpDirConf
    Jump to another directory conference 'J'


### JumpSubConf
    Jump to another sub conference.


### NewMsgsAllConfs
    Do a new message scan for all subs in all conferences '/A'


### UpDirConf
    Go to the next directory conference '}'


### UpSubConf
    Increment ()) to the previous conference number


## Category: EMail
***

### AttachFile


### KillEMail
    Kill email that you have sent 'K'


### MultiEMail
    Send multi-email


### ReadAllMail
    Sysop command to read all mail


### ReadEMail
    Read your email


### SendEMail
    Enter and send email 'E' from the main menu


## Category: File
***

### AllowEdit
    Sysop command to enter the 'ALLOW.DAT' editor.


### BatchMenu
    Enter the batch menu 'B'


### ConfigFileList
    Enter the List+ configurator so the user can set it up to look like he wants


### DirList
    List the directory names in the xfer section


### DLFile
    <dirfname> <filename>
    This will download a file, with a check for ratios and will update the
    kb downloaded and number of files downloaded.
    You must specify the dirfilename, which is the name of the data file in
    the transfer editor.  filename is the name of the file being downloaded.


### DLFreeFile
    <dirfname> <filename>
    This will download a file, but not check ratios or charge a download charge.
    You must specify the dir filename, which is the name of the data file in
    the transfer editor.  filename is the name of the file being downloaded.


### DownDir
    Go to the prior directory number '-'


### Download
    Download a file 'D'


### FindDescription
    Search for a file by description


### HopDir
    Hop to another directory number 'H'


### ListFiles
    List the file in the current directory


### ListUsersDL
    List users with access to the current xfer sub


### MoveFiles
    Sysop command to move files


### NewFilesAllConfs
    New file scan in all directories in all conferences


### NewFileScan
    List files that are new since your 'New Scan Date (usually last call)' 'N'


### PrintDSZLog
    View the DSZ log


### ReadIDZ
    Sysop command to read the file_id.diz and add it to the extended description


### RemoveFiles
    Remove a file you uploaded


### RemoveNotThere
    SYSOP command to remove files that do not exist.


### RenameFiles
    Sysop command to edit and rename files


### ReverseSortDirs
    Sort the directory by date or name, backwards.


### SearchAllFiles
    Search all files???


### SelectDir
    Like SelectSub, but for the xfer section.


### SetDirConf
    <key>
    Sets the xfer section conference to key


### SetDirNumber
    <key>
    Equivalent to typing in a number at the xfer menu, it sets the current dir
    number.


### SetNewFileScanDate
    Set the 'New Scan Date' to a new date


### SortDirs
    Sort the directory by date or name


### UpDir
    Go to the next directory number '+'


### Upload
    User upload a file


### UploadAllDirs
    Syosp command to add any files sitting in the directories, but not in
    the file database to wwiv's file database


### UploadCurDir
    Sysop command to scan the current directory for any files that are not in
    wwiv's file database and adds them to it.


### UploadFilesBBS
    Import a files.bbs (probably a CD) into the wwiv's file database


### UploadToSysop
    Upload a file into dir#0, the sysop dir.


### ViewArchive
    List an archive's contents


### XferDefaults
    Enter the xfer section defaults


## Category: GFiles
***

### BulletinEdit
    Sysop command to edit the bulletins 'gfiles'


### Bulletins
    Enter the bulletins (or 'gfiles') section.  'G'


## Category: Menu
***

### DisplayHelp
    An alias for DisplayMenu.
    This alias is deprecated, please use menu:display.


### DisplayMenu
    Prints the 'novice menus' for the current menu set, or if one doesn't exist,
    it will generate one using command "menu:generate_short"


### MENU
    <menu>
    Loads up and starts running a new menu set, where <menu> equals the name of
    the menu to load.


### menu:display
    Prints the 'novice menus' for the current menu set, or if one doesn't exist,
    it will generate one using command "menu:generate_short"


### menu:generate_long
    Generates the long form (one cmd per line) help text/menu for the current menu set.
    This command does not attempt to display a .msg/.ans file.


### menu:generate_short
    Generates the short form 'novice menus' for the current menu set.
    This command does not attempt to display a .msg/.ans file.


### ReturnFromMenu


## Category: Message
***

### ClearQScan
    Marks messages unread.


### DownSub
    Decrement the current sub number (-)


### HopSub
    Hop to another sub.  'H'


### ListUsers
    List users who have access to the current sub


### NewMessageScan
    Do a new message scan


### NewMsgScanCurSub
    Scan new messages in the current message sub


### NewMsgScanFromHere
    Read new messages starting from the current sub


### PostMessage
    Post a message in the current sub


### RemovePost
    Remove a post


### ResetQscan
    Set all messages to read (I think)


### SelectSub
    This will prompt the user to enter a sub to change to.  However, it does not
    first show the subs (like Renegade).  However, you can stack a sublist and
    then this command to mimic the action.


### SetMsgConf
    <key>
    Sets the subboards conference to key


### SetNewScanMsg
    Enter the menu so that a user can set which subs he want to scan when doing
    a new message scan


### SetSubNumber
    <key>
    Equivalent to typing in a number at the main menu, it sets the current sub
    number.


### SubList
    List the subs available


### TitleScan
    Scan the titles of the messages in the current sub


### UnQScan
    Marks messages as unread


### UploadPost
    Allow a user to upload a post that will be posted


### UpSub
    Increment the current sub# (+)


### ValidatePosts
    Sysop command to validate unvalidated posts


## Category: Net
***

### NetListing
    Show networks


### NetLog
    Sysop command to view the network log


### Pending
    Shows which net files are ready to be sent


## Category: QWK
***

### Packers
    Executes the QWK menu. (Legacy, use qwk: commands now)


### qwk:config_sysop
    Configures SysOp Settings for QWK


### qwk:config_user
    Configures User Settings for QWK


### qwk:download
    Download a QWK Message Packet


### qwk:menu
    Executes the default QWK menu.


### qwk:upload
    Upload a QWK Reply Packet


## Category: SYSOP
***

### ChainEdit
    Sysop command to edit the doors or chains


### ChangeUser
    Sysop command equal to //CHUSER, to change into another users


### ConferenceEdit
    Sysop command ot edit the conferences


### DirEdit
    Sysop command to edit the directory records


### Edit
    Sysop command to edit a text file


### MemStat


### Status


### SubEdit
    Sysop command to edit the subboards


### ToggleAvailable
    Toggle the sysop availability for chat


### ValidateUser
    Validate a new users.  I think this '!'


### ViewNetDataLog
    View the net data logs


### VoteEdit
    Sysop command to edit the voting both


## Category: System
***

### ChatRoom
    Go into the multiuser chat room


### cls
    Clear the screen


### Defaults
    Enter the normal 'defaults' section


### FastGoodBye
    Logoff fast '/O'


### Feedback
    Leave feedback to the syosp.  'F'


### Goodbye
    Normal logoff 'O'


### GuestApply
    Allows a guest to apply for access


### LastCallers
    View the last few callers


### ListAllColors
    Display all colors available for use.


### LoadText
    Sysop command to load a text file that will be edited in the text editor


### LoadTextFile
    Looks like a duplicate to 'LoadText'


### Log
    Syosp command to view the log file


### Pause
    Pauses the screen, like 'pausescr()' in C code


### PrintDevices
    Show the 'devices'.  I have no idea why.


### PrintFile
    <filename>
    Prints a file, first checking to see if you specified an absolute path,
    then the language dir, then the gfilesdir.  It will use the usual checks to
    determine .ANS, or .MSG if not specified.


### PrintFileNA
    <filename>
    Just like PrintFile, but the user can not abort it with the space bar.


### RequestChat
    Request chat from the sysop


### RunBasic
    <script name>
    Runs a WWIVbasic Script


### SystemInfo
    View the system info


### TextEdit
    Edit a text file


### TimeBank
    Enter the time bank


### ToggleExpert
    Turn 'X'pert mode on or off (toggle)
    Can optionally pass "quiet=on" as the command data to suppress displaying the expert mode state.


### TurnMCIOff
    Disable MCI codes


### TurnMCIOn
    Enable MCI codes


### WHO
    Show who else is online


### WWIVVer
    Get the wwiv version


### YLog
    View yesterdays log


### YourInfo
    Display the yourinfo screen


### YourInfoDL
    Prints user info for downloads


### ZLog
    View the ZLog


## Category: User
***

### ConfigUserMenuSet
    Takes the user into the user menu config so they can select which menuset
    they want to use, etc...


### user:address
    Allows the user to change their address


### user:ansistate
    Allows the user to change their ANSI state


### user:callsign
    Allows the user to change their HAM callsign


### user:city
    Allows the user to change their city


### user:comptype
    Allows the user to change their computer type


### user:country
    Allows the user to change their country


### user:dataphone
    Allows the user to change their data phone number


### user:editor
    Allows the user to change their default editor


### user:gender
    Allows the user to change their gender


### user:menus
    Takes the user into the user menu config so they can select which menuset
    they want to use, etc...


### user:qscan
    Allows the user to change their subs that are newscanned


### user:realname
    Allows the user to change their real name


### user:regnum
    Allows the user to change their WWIV 4.x registration number


### user:screensize
    Allows the user to change their screen size


### user:state
    Allows the user to change their state


### user:zipcode
    Allows the user to change their zipcode


## Category: Vote
***

### InitVotes


### Vote
    Enter the voting both


### VotePrint
    Show the voting statistics


