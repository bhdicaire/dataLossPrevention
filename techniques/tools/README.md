# Tools

## Testing Resource 

| Name   | HTTP Post | HTTPS Post | FTP |
| :-- |:--: | :--:| :--: |
|[DLP Test](https://dlptest.com/)| X | X | X |
|[NetMask.US](http://www.netmask.us/dlptest)| X | X | X |
|[Test the Proxy](http://www.testtheproxy.com/)| X | X | X |

## Scripts

### Create Random Files, Folders, and Subfolders with Depth

Trying to create dummy files, directories, and sub-directories that are randomly N levels deep.

There should be files in each directory/sub-directory.

I was able to provide a directory and get random folders created with random files inside, but having trouble with the loop to go N levels deep.

Information but no working code:
 * https://serverfault.com/questions/990751/powershell-create-random-files-folders-and-subfolders-with-depth
 New-Item -ItemType Directory -Path C:\NewPath\NewSubPath\AnotherSubDir\WowThisIsReallyNested -Force
 

| Description| Path | 
| :-- | :-- |
|[Folders structure with random files using Powershell](https://social.technet.microsoft.com/wiki/contents/articles/37233.random-folders-structure-with-random-files-using-powershell.aspx)| [](https://github.com/bhdicaire/dataLossPrevention/blob/main/techniques/tools/randomStructure.ps)

Create-RandomFiles using Powershell
https://github.com/donnietaylor/Create-RandomFiles

### Pick random items from one of the dataSet
