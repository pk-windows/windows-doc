# Windows Help documentation

1. [Batch](batch/batch.md)

## Command Prompt / Batch Window

Display only the current directory name (not the full path) in Windows Batch Prompt. 
Ex:

```batch
C:\users\Pradeep\home\workspace>
```

to

```batch
workspace>
```

Run command in prompt

```batch
C:\users\Pradeep\home\workspace> PROMPT=workspace$G
workspace>
```