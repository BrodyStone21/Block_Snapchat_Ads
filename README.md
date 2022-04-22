## Block_Snapchat_Ads
A domain list created to block ads within Snapchat through Pi-hole. Feel free to follow the below steps to add the list to your installation, or use the domains on the list as a starting point for your own list.

This was tested on a Google Pixel 5. There are no obvious issues I've discovered. I'm still able to send/receive snaps, and notifications are working fine. I'm located on the East Coast so I've whitelisted a few East Coast servers. Depending on your geography, you may have to add more to this list. 

Please let me know of any issues and I'll do my best to implement the changes in a timely manner.

### How to add to Pi-hole
1. Navigate to the Pi-hole Web UI
2. Click "Group Management" 
3. Click "Adlists"
4. Where it asks for an address, enter this: https://raw.githubusercontent.com/BrodyStone21/Block_Snapchat_Ads/main/domains/whitelist.txt
5. Click "Tools"
6. Click "Update Gravity"
7. Click "Update"

### Note: 
Please ensure you clear Snapchat's cache and force stop the app within your system settings to ensure this works. 

### My Stories/Discover page isn't loading new content?
To force your Discover/Stories page to load new content, you must either temporily disable Pi-hole, or connect to a network that is not blocking these domains (such as your mobile data). Then you must open the app, and refresh the Discover page. After this, you can renable Pi-hole. 
