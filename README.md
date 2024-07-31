# Invin-Injector

Invin-Injector is a powerful and versatile WordPress plugin designed for advanced users and security professionals to facilitate file uploads and command execution directly from a WordPress page. This plugin is primarily aimed at users who need to perform security assessments, penetration testing, or manage remote systems through a web interface.

# Reason behind building this plugin

As a penetration tester, I often encounter scenarios where exploiting WordPress becomes a critical task to gain administrative access and achieve further control over a system. The challenge of uploading shells or obtaining reverse shell access highlights the need for advanced tools that streamline these processes. This motivation led me to develop the Invin Injector plugin, designed to facilitate file uploads and command executions directly from within WordPress. By addressing these common exploitation techniques in a controlled manner, I aim to enhance the efficiency and effectiveness of security assessments and testing.

# Key Features:

1. File Upload Functionality:
   - Allows users to upload files directly through a WordPress page.
   - Provides an easy-to-use interface for selecting and uploading files.
   - Displays the path of the uploaded files for easy reference.

2. Command Execution:
   - Execute Linux or Windows commands depending on the operating system specified.
   - Provides a terminal-like interface within the WordPress page for running commands.
   - Outputs the results of the command execution in a styled, readable format.

3. OS-Specific Commands:
   - Linux Commands: Supports executing shell commands on Linux-based servers.
   - Windows Commands: Executes CMD commands on Windows-based servers, including PowerShell scripts if required.

4. Customizable Interface:
   - Includes options for displaying command output in a customizable, styled box.
   - Supports various styling options to enhance readability and presentation of the output.

# Usage:

1. Installation:
   - Upload the plugin files to the `/wp-content/plugins/` directory.
   - Activate the plugin through the 'Plugins' menu in WordPress.

2. Configuration:
   - Navigate to the plugin settings page to configure OS-specific command execution.
   - Select the desired operating system to tailor the command execution environment.

3. Usage:
   - Add the `[invin]` shortcode to any WordPress page or post where you want the file upload and command execution interface to appear.
   - Use the interface to upload files and execute commands as needed.

# Disclaimer:

- Security Warning: This plugin provides powerful capabilities that should be used responsibly. Ensure that it is used in secure environments and that appropriate access controls are in place. Unauthorized use of this plugin can lead to severe security risks.
- Testing: The plugin has been tested on live targets in controlled environments. Ensure you comply with all legal and ethical guidelines when using this plugin in production environments.


-----------------------------------------------------

Tested on live Target here are some samples

![Tested-1](https://github.com/user-attachments/assets/c09e96a4-5e38-421b-9e1d-c500d43d0f20)


![Tested-2](https://github.com/user-attachments/assets/e7eb1abc-324b-4ef5-b402-1d945019376a)




