# Graylog-OPNsense_Extractors
Extractors for Graylog to parse OPNsense logs.

Using [https://github.com/IRQ10/Graylog-OPNsense_Extractors](https://github.com/IRQ10/Graylog-OPNsense_Extractors) for firewall rule parsing.

1. HAProxy Public Service Extractor

## Usage
1. Open Graylog. Navigate to the input you wish to run the extractor on.
2. Click on "Manage extractors". 
3. Drop down "Actions" in the top right corner, then click "Import extractors"
4. Paste the contents of the desired JSON file into the box. Click "Add extractors to input"
5. **If using RFC 5424 logs**: Navigate back to the input, click "More actions' > "Edit input", and ensure "Store full message?" is enabled.