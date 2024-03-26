<h1 color="red">Disclaimer: By utilising any of these steps, you agree you will not conduct any illegal activity and anything you do, I am not responsible for. This is simply just information that I have collected.</h1>

<h2>Introduction</h2>
<p>Nowdays, most of the stuff we click on is logged and monitored in some sort of way. This is done so discretely that it is not meant to be seen. Most people do not want this, but have no idea how much information is being logged. Most of your network activity goes through your ISP. This is a guide on how to safely browse anonymously online and each step increases your protection. But first, we need to do some learning.</p>

<h2>Fingerprints</h2>
<p>Let's say you commit a crime and forensics sweep the place and collect your fingerprints from the crime scene. These fingerprints are uniquely identifiable to you and you only. This is similiar to the following points, but instead, these are constantly being logged. Note that the following exmaples are not all the things that make you uniquely identifiable, but are the most common.</p>
<ul>
  <li><b>IP Address: </b> Every device connected to the interent is assigned a unique IP address. There are two types of IP addresses:
    <ul>
      <li><b>Private</b> A private IP address is an address assigned to a device within a private network, such as a home network. These addressess are not global and can only be used on the private network. These tend to look like <b>192.168.0.2</b> or <b>192.168.0.102</b>.</li>
      <li><b>Public:</b> A public IP address is an address that is assigned to a device also connected to the internet. It uniquely identifies the device on the global internet, allowing it to communicate with other devices and servers worldwide. These typically look like <b>169.140.196.142</b></li>
    </ul>

The public IP address serves as an identifier for the device and can provide information about its geographical location. As an example, open <a target="_blank" href="https://www.geolocation.com/">this</a> website and see if it accuractely shows your location. Scary, right? Websites and online services can log IP addresses when users access their content, which can then be used to track and identify individuals.</li>

<li><b>MAC Address: </b> MAC stands for Media Access Control, and is another unique identifier. Although unlike IP addresses, MAC addresses are primarily used for communication within local networks. Devices on the same local network (like your home Wi-Fi) can see each other's MAC addresses because they are necessary for directing traffic within that network. However, MAC addresses are not visible beyond the local network. MAC addresses often look like: <b>3A-34-52-C4-69-B8</b>.</li>

<li><b>Cookies:</b> Cookies are small pieces of data stored on a user's device by websites they visit. These cookies can contain information such as login credentials, site preferences, and browsing history. While they're not able to uniquely identify on their, cookies can be used to track user activity across websites and build up a profile of their behavior and interests.</li>
</ul>

<h2>1. VPN</h2>
<p>Most of you have heard about a VPN. This stands for Virtual Private Network. Usually, when you go online, your device connects to the internet directly through your ISP. Your data travels from your device, through your ISP's servers, and then out onto the internet. When you use a VPN, it's like putting a secure tunnel around your internet connection. Instead of connecting directly to your interent, your device first connects to a server operated by the VPN provider, which travels through an encrypted tunnel. This means that anyone trying to spy on your internet activity (including ISP and hackers), cannot see what you're doing as it is encrypted. The VPN server acts as a middleman between your device and the internet. When you access websites or online services, it appears as though your requests are coming from the VPN server's location rather than your actual location. A VPN also hides your real IP address, which makes it so much harder for other to track what you're doing. If you want to maximise your security, a paid VPN is the best option, although if that is not an option, free ones are better than nothing. Remember, when signing up to your VPN, never use your actual details. You can use a temporary <a href="https://10minutemail.com/" target="_blank">10 minute email</a> to sign up. If you want to test if your VPN is good, go ahead and connect to it, navigate to <a href="https://vpntesting.com/">this</a> webiste and run the scan.

  <h3>Paid VPNs</h3>
  <ul>
    <li><b>Express VPN</b></li>
    <li><b>Nord VPN</b></li>
    <li><b>SurfShark</b></li>
    <li><b>CyberGhost</b></li>
  </ul>

  <h3>Free VPNs</h3>
  <ul>
    <li><b>Proton VPN</b></li>
    <li><b>TunnelBear</b></li>
    <li><b>Speedify</b></li>
  </ul>
</p>

<h2>2. Browser and search engine</h2>
<p>If you want the most security possible, you can use a browser called <a href="https://www.torproject.org/download/"><b>TOR browser</b></a>. This browser works by routing your networking traffic through multiple servers and locations, encrypted throughout the way. TOR is not a common browser as it is often used to conduct illegal activity due to how secure it is, but it is totally legal and a super good way to protect yourself. TOR is also pretty slow due to the routing so it may not be ideal for the average user. TOR may also be a bit overkill for the average user. Note, it is not recommended to install extensions on the TOR browser, as it can compromise security.

Now if this is not as of interest to you, the next best option is FireFox. Firefox has built-in tracking protections, good privacy settings, and a bunch of good add-ons for privacy, which I will talk about later. FireFox is a better and more private option to Chrome. The default search engine for FireFox is Google. You want to change this to DuckDuckGo, which unlike Google, doesn't track or store your personal information. This means your searches are not tied to your identify. DuckDuckGo also has no personalised Ads.</p>

<h2>3. Browser Extensions</h2>
<p>If you chose the FireFox option, you will want to install some additional extensions to secure yourself even more. You can do this by going to the <a href="https://addons.mozilla.org/en-US/firefox/extensions/">FireFox extension store</a>. Here are the extensions you want to install (all free):
  <ul>
    <li><b>UBlock Origin: </b>Block all ads everywhere.</li>
    <li>Privacy Badger<b>: </b>This extension blocks all invisible trackers.</li>
    <li><b>Anti-AdBlocker Blocker: </b>Some sites detect you are utilising an AdBlocker. This extension blocks them from knowing.</li>
    <li><b>AdBlock Plus: </b>Another AdBlocker to be sure all those pesky ads are blocked.</li>
  </ul>
</p>

<h2>4. Tails OS</h2>
<p><a href="https://tails.net/">Tails OS</a> is an linux distro focused on privacy. To create Tails OS, you have to create a bootable USB. You can create a virtualbox but Tails OS <a href="https://tails.net/doc/advanced_topics/virtualization/virtualbox/index.en.html">documentation warns against it</a> due to potential privacy complications. Once you have created a bootable Tails OS USB and have booted your computer with it, you can follow the above steps for VPNs and browsing. Although if you are prepared to go this far, you may aswell use TOR browser in Tails.</p>

<h2>5. Route activity through TOR network.</h2>
<p>This option is again an extreme option. You can actually route all your network activity through the TOR network. It is a little complex to explain it all on here, but if you want to go the extra step, you can search up guides... There are loads.</p>

<h2 color="red">All furthur steps are for maximum privacy, usually to be utilised only by professionals.</h2>

<h2>Extreme Privacy & Security</h2>
<p>Now if you are super super concerned about your privacy, this is an extreme measure and is not usually used.
  <ul>
    <li><b>Buy 2 cheap laptops: </b>Purchase two cheap laptops, in person and in cash.</li>
    <li><b>Go to public Wi-Fi: </b>Travel to a public network with your bootable Tails OS USB and VPN.</li>
    <li><b>Setup hotspot: </b>One one laptop, connect to the public network and setup a hotspot. This should also be connected to a VPN.</li>
    <li><b>Boot Tails OS on other laptop: </b>Boot into your Tails OS laptop, connect to the hotspot you just setup.</li>
    <li><b>Connect VPN: </b>Now connect your VPN and enjoy your private browing experience.</li>
  </ul>
</p>
