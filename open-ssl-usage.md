powershell -command "[System.BitConverter]::ToString([System.Text.Encoding]::ASCII.GetBytes('2511251125112511'))"

<nul set /p="silleno" | openssl enc -aes-128-cbc -a -nosalt -K 32353131323531313235313132353131 -iv 00000000000000000000000000000000
