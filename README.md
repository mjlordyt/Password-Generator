# Password-Generator

Password Generating Tool 🔐
A simple yet powerful Bash script that utilizes the crunch tool to generate customizable password lists. Ideal for penetration testers, ethical hackers, and security enthusiasts who need secure and flexible password generation.

Features
✅ User-friendly interface with color-coded prompts and ASCII art.
✅ Set minimum and maximum length for generated passwords.
✅ Customize your password character set (e.g., abc123!@#).
✅ Displays estimated file size and total number of passwords before generation.
✅ Saves output to a file for easy access.
✅ Lightweight and efficient for generating large password lists.

Prerequisites

Linux/Unix Environment with Bash.

Install the following tools:
crunch: Password generation utility. 

Install with:
sudo apt-get install crunch
toilet (for ASCII art) and lolcat (for color effects).

Install with:
sudo apt-get install toilet
gem install lolcat
cowsay (optional, for fun exit messages):
sudo apt-get install cowsay

How to Use

Clone the repository:
git clone https://github.com/mjlordyt/Password-Generator.git
cd password_generating

Make the script executable:
chmod +x password_generator.sh

Run the script:
./password_generator.sh

📸 Colorful Banner:
Showcases an engaging banner and ASCII art during execution.

📸 Interactive Input Prompts:
Users can enter their desired length range and character set interactively.

📸 Output Files:
Save generated passwords directly into a text file.

Disclaimer
This tool is designed for ethical purposes only. Use responsibly and in compliance with all applicable laws and guidelines.

Contributions
Feel free to fork this repository and submit pull requests for improvements or feature requests.

License
This project is licensed under the MIT License. See the LICENSE file for details.
