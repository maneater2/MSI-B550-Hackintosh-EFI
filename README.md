# MSI B550 Hackintosh EFI

## Reminder!!!

### For more security, consider adding a password, an unique ApECID, maybe even add a vault. Remember that you might need a Disabled SecureBootModel to install macOS

- For passwords, use the tool "ocpasswordgen" included in OpenCorePKG

- For ApECID, run this command:
  `python3 -c 'import secrets; print(secrets.randbits(64))'`

- For vaults, put your EFI in a unzipped OpenCorePkg folder, and run sign.command in the CreateVault directory
