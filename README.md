# killMicrosoftTeams

This bash script is designed to delete specific folders associated with the Microsoft Teams application on macOS. It is useful for cleaning caches and other temporary files to troubleshoot issues or free up space.

## Usage

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone git@github.com:elionaz/killMicrosoftTeams.git
cd killMicrosoftTeams
```

### 2. Make the Script Executable

Before running the script, ensure it has execution permissions. You can do this with the following command:

```bash
chmod +x killMicrosoftTeams.sh
```

### 3. Run the Script

To run the script and delete the folders related to Microsoft Teams, use:

```bash
./killMicrosoftTeams.sh
```

### 4. Folders Deleted

The script will delete the following folders:

- `~/Library/Caches/com.microsoft.teams`
- `~/Library/Caches/com.microsoft.teams.shipit`
- `~/Library/Application Support/Microsoft/Teams`
- `~/Library/Application Support/Microsoft/Teams/Application Cache/Cache`
- `~/Library/Application Support/Microsoft/Teams/blob_storage`
- `~/Library/Application Support/Microsoft/Teams/Cache`
- `~/Library/Application Support/Microsoft/Teams/databases`
- `~/Library/Application Support/Microsoft/Teams/GPUCache`
- `~/Library/Application Support/Microsoft/Teams/IndexedDB`
- `~/Library/Application Support/Microsoft/Teams/Local Storage`
- `~/Library/Application Support/Microsoft/Teams/tmp`

### 5. Warning

This script will delete the specified files and folders without the possibility of recovery. Use it with caution.

## Contributions

Contributions are welcome. If you have improvements or suggestions, feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
