<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>
	<p><strong>|</strong> <strong>Create A Bot</strong></p>
	<ol>
		<li>Go to this <u>page</u> and sign in to your discord account.</li>
		<li>Click the <strong>New Application</strong> top right of your screen.</li>
	</ol>
	<p><img src="https://i.imgur.com/fzlrdqV.png"></p>
	<ul>
		<li>Next enter the name of your bot and click create.</li>
	</ul>
	<p><img src="https://i.imgur.com/LR6rIWs.png"></p>
	<ul>
		<li>Next, click the <strong>Bot</strong> tab to the left and click <strong>Add Bot</strong> to the right of that page.</li>
	</ul>
	<p><img src="https://i.imgur.com/OqR63ux.png"></p>
	<p><strong>|</strong> <strong>Frequently Asked Questions</strong></p>
	<p>Where is the <strong>TOKEN</strong>?</p>
	<ol>
		<li>Go to the bot application you just created.</li>
		<li>Click the <strong>Bot</strong> tab on the left of the screen.</li>
		<li>Then look for the word <strong>TOKEN</strong>, and click the Copy under it.</li>
	</ol>
	<p><img src="https://i.imgur.com/YI9Ijnd.png"></p>
	<p>Where is the <strong>CLIENT ID</strong>?</p>
	<ol>
		<li>Go to the bot application you just created.</li>
		<li>Click the <strong>General Information</strong> tab on the left of the screen.</li>
		<li>Then look for the word <strong>CLIENT ID</strong>, and click the Copy under it.</li>
	</ol>
	<p><img src="https://i.imgur.com/oLPw86e.png"></p>
	<p>Where is the <strong>INVITE LINK</strong>?</p>
	<ol>
		<li>Go to the bot application you just created.</li>
		<li>Click the <strong>OAuth2</strong> tab on the left of the screen.</li>
		<li>Then look for the word <strong>Scopes</strong>, and click the <strong>bot</strong> option.</li>
		<li>You should see a link pop up at the bottom of <strong>scopes</strong>, click Copy.</li>
	</ol>
	<p><img src="https://i.imgur.com/NMTlsN3.png"></p>
	<p><strong>|</strong> <strong>Windows Hosting Tutorial</strong></p>
	<ol>
		<li>Make sure you have <u>node.js</u> installed.</li>
		<li>Create a file on your desktop, and import all bot files into it.</li>
		<li>Next, get the file’s directory.</li>
	</ol>
	<p><img src="https://i.imgur.com/WQ3ZAvg.png"></p>
	<ul>
		<li>Open a command prompt and type in cd . Exclude the &lt;&gt;.</li>
		<li>Next enter the command npm install into the command prompt.</li>
		<li>Finally, to turn the bot on, enter the command node . and click enter.</li>
		<li>To close the bot click Ctrl + C or just close the cmd window.</li>
	</ul>
	<p><strong>|</strong> <strong>Ubuntu Hosting Tutorial</strong></p>
	<p></p>
	<blockquote>
		Bot files have to be uploaded first.
	</blockquote>
	<p></p>
	<ol>
		<li>Enter your terminal or SSH.</li>
		<li>Run all the commands below.
			<ol>
				<li>sudo apt-get install curl</li>
				<li>curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -</li>
				<li>sudo apt-get install -y nodejs</li>
				<li>sudo npm install pm2@latest -g</li>
				<li>Then enter the bot files with cd . Exclude the &lt;&gt;.</li>
				<li>Lastly, run the command pm2 start &lt;.js file name&gt;. Exclude the &lt;&gt;.</li>
				<li>To turn the bot off or restart it use pm2 stop or pm2 restart . Exclude the &lt;&gt;.</li>
			</ol>
			<p><strong>|</strong> <strong>Debian Hosting Tutorial</strong></p>
			<p></p>
			<blockquote>
				Bot files have to be uploaded first.
			</blockquote>
			<p></p>
		</li>
		<li>Enter your terminal or SSH.</li>
		<li>Run all the commands below.</li>
		<li>curl -sL https://deb.nodesource.com/setup_12.x | sudo bash -</li>
		<li>sudo apt-get install -y nodejs</li>
		<li>sudo npm install pm2@latest -g</li>
		<li>Then enter the bot files with cd . Exclude the &lt;&gt;.</li>
		<li>Lastly, run the command pm2 start &lt;.js file name&gt;. Exclude the &lt;&gt;.</li>
		<li>To turn the bot off or restart it use pm2 stop or pm2 restart . Exclude the &lt;&gt;.</li>
	</ol>
	<p><strong>|</strong> <strong>CentOS Hosting Tutorial</strong></p>
	<p></p>
	<blockquote>
		Bot files have to be uploaded first.
	</blockquote>
	<p></p>
	<ul>
		<li>Enter your terminal or SSH.</li>
		<li>Run all the commands below.</li>
		<li>curl -sL https://rpm.nodesource.com/setup_12.x | sudo bash -</li>
		<li>sudo npm install pm2@latest -g</li>
		<li>Then enter the bot files with cd . Exclude the &lt;&gt;.</li>
		<li>Lastly, run the command pm2 start &lt;.js file name&gt;. Exclude the &lt;&gt;.</li>
		<li>To turn the bot off or restart it use pm2 stop or pm2 restart . Exclude the &lt;&gt;.</li>
	</ul>
</body>
</html>