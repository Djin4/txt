# Go to your home directory
cd ~

# Download Clash binary (64-bit)
wget https://github.com/Dreamacro/clash/releases/latest/download/clash-linux-amd64-v3.gz

# Extract it
gunzip clash-linux-amd64-v3.gz

# Make it executable
chmod +x clash-linux-amd64-v3

# Move to system path
sudo mv clash-linux-amd64-v3 /usr/local/bin/clash
