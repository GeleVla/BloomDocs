---
id: server-importer
slug: /server-importer
title: Server Importer
hide_title: true
hide_table_of_contents: true
sidebar_label: Server Importer
image: https://bloom.host/assets/images/logo.png
---

<div class="text--center">
<img src="https://bloom.host/logo-white.svg" alt="logo" height="50%" width="50%"/>
<h1>Server Importer</h1>
</div>

### How it works

Duck Panel has a convenient server importer feature. The server importer allows you to easily import your server into Bloom, saving time and avoiding having to download/upload files yourself.

:::note
You can also import the databases hosted on your old host! Follow this [guide](https://docs.bloom.host/databases#importing-mysql-databases) to see how to import databases.
:::

---

### Remote S/FTP credentials
First you will need the credentials to connect to the remote S/FTP server. If you are importing from another game host, this information should be located in their panel. You will need the following details:
- Server type (FTP, FTPS or SFTP)
- Host and Port
- Username
- Password

:::note
We recommend you compress all the server files that you want to import before starting. Many game host panels support the ability to compress your files. This will greatly increase the speed of the server import.

#### How to start the server import
- First go to our [Duck Panel](https://mc.bloom.host)
- Select the server to which you want to import the files.
- Click on "*Server Importer*" on the navigation bar.
- Fill in the form with your the appropriate credentials.
- Leave the "Base Directory" on `/` if you want to import all the files. If you want to import a specific file or folder, you can specify that in this box.

Once the import begins, you an navigate to the Console page to view the current progress.

<div class="text--center"><img src={require('../../static/imgs/using_the_panel/server-importer/1.png').default} alt="console"/></div>
