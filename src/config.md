# Configuration guide

- [Homefiles](#homefiles)

## Homefiles

> The "Homefiles" key contains an array with the informations about the files located ah /home/$USER/

### Structure

```yaml
homefiles:
    - name: "I3 configuration" # String: The name of the file (optional)
      path: .config/i3/config # String: The path to the file / directory
      backuponly: false # Use true if you want the file to not be reinstalled with `kelpdot install` (optional) (default: false)
      onlyon: gentoo # Specify if the file can only be installed in one distro (optional) (default: None)
```
