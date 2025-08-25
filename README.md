# Unifi Dream Machine Console Script for System Monitoring

![GitHub release](https://img.shields.io/github/v/release/ASrivastavaweb/UnifiDreamMachine?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-brightgreen)
![Issues](https://img.shields.io/github/issues/ASrivastavaweb/UnifiDreamMachine)

## Overview

This repository contains a bash script designed to run on the Unifi Dream Machine console. It provides real-time monitoring of system status, including temperature, sensors, and overall system health. The script aims to simplify the process of checking system metrics for Ubiquiti's Unifi controller.

## Features

- **System Status Monitoring**: Quickly check the status of your Unifi Dream Machine.
- **Temperature Readings**: Get real-time temperature data to ensure your device operates within safe limits.
- **Sensor Data**: Access various sensor readings to maintain optimal performance.
- **Easy to Use**: Run the script directly in the console with minimal setup.

## Getting Started

To get started, download the latest release of the script from the [Releases section](https://github.com/ASrivastavaweb/UnifiDreamMachine/releases). 

1. Navigate to the [Releases section](https://github.com/ASrivastavaweb/UnifiDreamMachine/releases).
2. Download the script file.
3. Open your console on the Unifi Dream Machine.
4. Execute the script using the command:

   ```bash
   bash path/to/downloaded/script.sh
   ```

## Installation

To install the script, follow these steps:

1. **Download the Script**: Visit the [Releases section](https://github.com/ASrivastavaweb/UnifiDreamMachine/releases) to find the latest version.
2. **Move the Script**: Place the downloaded script in a directory of your choice, preferably in a location that is easy to access.
3. **Make it Executable**: Run the following command to make the script executable:

   ```bash
   chmod +x path/to/script.sh
   ```

4. **Run the Script**: Execute the script using:

   ```bash
   ./path/to/script.sh
   ```

## Usage

Once the script is running, it will display various metrics about your Unifi Dream Machine. Here’s what you can expect:

- **Current Temperature**: Displays the current temperature of the device.
- **Sensor Status**: Shows the status of various sensors integrated into the Dream Machine.
- **Overall System Health**: Provides a summary of the system's performance metrics.

### Example Output

```plaintext
System Status:
---------------
Temperature: 60°C
Fan Speed: 1200 RPM
CPU Usage: 25%
Memory Usage: 40%
```

## Topics Covered

This script addresses several topics relevant to system monitoring:

- **Bash**: The script is written in Bash, making it easy to modify and extend.
- **System Status**: It focuses on providing real-time insights into the system's health.
- **Ubiquiti & Unifi**: Tailored specifically for Ubiquiti's Unifi products, ensuring compatibility and performance.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request. 

### Steps to Contribute

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes.
4. Commit your changes with clear messages.
5. Push to your fork and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the Ubiquiti community for their ongoing support and contributions.
- Special thanks to contributors who have improved this script over time.

## Support

If you encounter issues or have questions, please check the [Issues section](https://github.com/ASrivastavaweb/UnifiDreamMachine/issues) or create a new issue.

## Additional Resources

- [Ubiquiti Official Documentation](https://www.ui.com/download/unifi)
- [Bash Scripting Guide](https://www.tldp.org/LDP/Bash-Beginners-Guide/html/)
- [Unifi Community Forum](https://community.ui.com/)

## Related Projects

- [Unifi Network Controller](https://github.com/ubnt/intended-use)
- [Ubiquiti Device Monitor](https://github.com/ubnt/monitor)

## Contact

For further inquiries, feel free to reach out via GitHub or through the Ubiquiti community forums.

![Unifi Dream Machine](https://www.ui.com/wp-content/uploads/2020/06/unifi-dream-machine-1.png)

## Disclaimer

This script is provided as-is without any warranty. Use it at your own risk.

## Future Plans

- Add support for additional sensors.
- Improve output formatting for better readability.
- Include logging capabilities to track historical data.

---

Visit the [Releases section](https://github.com/ASrivastavaweb/UnifiDreamMachine/releases) to download the latest version of the script and start monitoring your Unifi Dream Machine today!