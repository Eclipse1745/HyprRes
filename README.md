HyprRes

HyprRes is a Bash script designed to simplify the process of changing display resolutions in the Hyprland window manager. By providing an interactive interface, it eliminates the need to manually edit configuration files, streamlining the user experience.
Features

    Interactive Selection: Utilize fzf for a user-friendly selection of monitors, resolutions, and refresh rates.

    Automatic Configuration: Updates the Hyprland configuration file automatically based on user selections.

    Immediate Application: Applies the new settings without requiring a manual restart of Hyprland.

Dependencies

Ensure the following packages are installed on your system:

    fzf: A command-line fuzzy finder for interactive selections.

    hyprctl: A command-line utility to interact with the Hyprland compositor.

Installation

    Clone the Repository:

git clone https://github.com/Eclipse1745/HyprRes.git

Navigate to the Directory:

cd HyprRes

Make the Script Executable:

chmod +x hypr-res

Move the Script to a Directory in Your PATH (e.g., /usr/local/bin):

    sudo mv hypr-res /usr/local/bin/

Usage

    Run the Script:

    hypr-res

    Follow the Prompts:

        Monitor Selection: Choose the desired monitor from the list.

        Resolution Selection: Pick the preferred resolution for the selected monitor.

        Refresh Rate Selection: Select an appropriate refresh rate for the chosen resolution.

    Apply Settings: The script will update the Hyprland configuration and apply the new settings immediately.

License

This project is licensed under the GPL-3.0 License. For more details, refer to the LICENSE file in the repository.

Note: Always ensure you have backups of your configuration files before making changes. 
