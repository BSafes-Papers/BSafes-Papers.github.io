---
layout: default
title: Chapter IV - Data Presentation and Analysis
parent: § Evaluating Security in Cryptocurrency Wallets  
grand_parent: Cryptocurrency 
has_children: true
nav_order: 40
---
<style>
.dont-break-out {
  /* These are technically the same, but use both */
  overflow-wrap: break-word;
  word-wrap: break-word;

  -ms-word-break: break-all;
  /* This is the dangerous one in WebKit, as it breaks things wherever */
  word-break: break-all;
  /* Instead use this non-standard one: */
  word-break: break-word;
}

.youtube-container {
    position: relative;
    width: 100%;
    height: 0;
    padding-bottom: 56.25%;
}
.youtube-video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

</style>

<div class="dont-break-out" markdown="1">

1. TOC
{:toc}

## Chapter IV: Data Presentation and Analysis

### Introduction
In this chapter, results of the testing will be logged and evaluated; the following websites, apps, and hardware wallets were tested using the OWASP Top 10 Iot testing device guidelines and were described in the previous chapter as follows: web-based, hardware, app-based, and paper wallets.

### Data Presentation
This section shows tables containing test results from all the web-based, hardware wallets, and app-based wallets cryptocurrency wallets for the starred paper. The following shows a summary of findings for each device, smartphones, paper wallets and website which I tested below.

**Online or Web-based Wallets**
They are a type of electronic card which is used for transactions made online; Its utility is the same as a credit or debit card, it primarily has two components, the first is software, and the second is information. The software component stores personal information and provides security and encryption of the data, whereas the information component is a database of details provided by the user which includes their name, home address, payment method, amount to be paid, credit or debit card details, etc. These wallets are vulnerable, and it is recommended not to leave a large amount of crypto token to this wallet. It does have some advantages and disadvantages:

Advantages:
- The transactions are completed in short period of time.

- It is recommended to store a small amount of cryptocurrency or token into your wallet. 

- Some of these digital wallets are suitable for storing several different cryptocurrencies and making transfer between them. 

- They require you to input your PIN to authorize payment or any transactions. For devices with biometrics, a payment would require your fingerprint to authorize it

- It can be very convenient for travelers. If your electronic wallet accepts your payment card and you are traveling abroad, the country you are visiting most likely will be able to use your electronic wallet as payment information too.

- Possibility of using TOR network for more privacy. 

Disadvantages: 

- The full control of digital wallet is in the hand of the third party, and it is not available worldwide. 

- It is recommended to use a personal computer when using a digital wallet and it is important to have security software installed. 

- It does not eliminate the security risks because of the Lack of knowledge in information technologies that leads users to the risk of various online frauds.

Each of these seven web-based wallets were tested while using the OWASP Top 10 Iot devices framework as a guideline.

1. **Metamask.** It is a tool that users need to access and connect to new types of applications; It is a wallet that keeps the valuable data and safe and secure, it is a shield that protects against hackers and data collectors. It is a very safe a secure way to connect to blockchain-based applications. The users are in control when interacting on the new decentralized web, and they control their own identity. No more new passwords when you visit the site, because what the Metamask does is that it can generate passwords and keys on the device so the users can only have access to their account and data (Salvo, 2020).

    Users are free to choose what they want to share and what they want to keep private. Metamask has a secret phrase with twelve words that controls your account. The secret phrase is uses for the login, and the password is the proof of your ownership all included in one. It is very important to keep the secret password in an extremely safe place as you easily access it, and it would be safer there. This wallet operates over myriads of browsers such as Google Chrome, Mozilla Firefox, Brave, and Opera browsers. The example is shown on Figure 6 below:

    **Figure 6**  
*Metamask Secret Phrase (Senishin, 2019)*
    ![Metamask Secret Phrase (Senishin, 2019)](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-fig-6.png)

    ***Identification:***
    ➢ The new version 8 of Metamask wallet allows users to decide what each site has access to. 

    ➢ This new feature enables you to easily switch between accounts, so you can control which accounts interacts with different sites across the decentralized web. 

    ➢ It allows websites to encrypt and decrypt messages intended for web 3 users. 

    ➢ LavaMoat was built into the new wallet which is a set of tools to prevent cyber-attacks.

    ***Quantification:***
    ➢ Using a private key 

    ➢ Modify the user model; sign a precise piece of data generated by our back end. 

    ➢ Back-end will consider you of that public address. 

    ➢ Signing based authentication mechanism with a user public address as their identifier 

    ➢ Available plugin on Metamask Chrome extension or Firefox add-on 

    ➢ It serves as Ethereum wallets, you will get access to a unique Ethereum public address which you can send and receive Ether or tokens. 

    ➢ New encryption feature for developers and boosted the app’s security with its new LavaMoat tool.

2. **Blockchain.info**. The most popular crypto wallet where you can only have control over your crypto and your private key is blockchain. With this blockchain, you can buy, sell, send, receive, exchange, store, and switch between cryptocurrencies without leaving the security of your own wallet. Based on this blockchain security, there are a few steps that need to be taken into consideration; these steps can be that you only have access to your private keys and your crypto; or that you can set up a four-digit PIN number wherein you have a backup and recovery with your unique twelve-word backup phrase. Finally, you could choose to avoid security breaches with the advanced two-factor authentication system.

    ***Identification:***
   ➢ It is easy to use. It is just like any other software or a wallet that you use for your day-to-day transactions. 

    ➢ It is very secure, and it is just a matter of securing your private key. 

   ➢ It Allows instant transaction across geographies; There are low transactions fees; the cost of transferring funds is much lower than with a traditional bank. 

    ➢ It allows transactions across multiple cryptocurrencies. This will help on an easy currency conversion.

    ***Quantification:***
    ➢ Software wallets and hardware wallets which you plug into a USB drive. 

    ➢ Paper based wallets in which you print your public and private key on a piece of paper to keep it in a secure area.

    ➢ They are two types of Blockchain which are hot and cold wallets.

    ➢ Hot wallet which Cryptocurrency can be transferred quickly; private keys are stored in the Cloud for fast transfer. 

    ➢ It has an easy access but has a risk of unrecoverable theft when hacked. 

    ➢ It does have a Cold wallet where the transaction is signed offline and later disclosed online; private keys are stored in a hardware. 

    ➢ This transaction helps in protecting the wallets from authorized access and other vulnerabilities.

3. **MEW(MyEtherWallet).** MEW is a free client-side wallet that is used to interact with the Ethereum blockchain while you control your own keys and funds. It allows you to generate wallets, interact with smart contract. It is not a bank or an exchange app. You are the one who is in control or in charge of it. You are the one who holds the keys, funds, and personal information. It means that MEW cannot have access to the accounts, your recovery keys, your reset passwords, or any transaction. For security purpose, it is important that every user write their keys and passwords down and save it in a secure area. Do not store your key’s information on a computer or phone.

    ***Identification:***
    ➢ It is a process which begins with the generation of your Crypto Wallet key 

    ➢ This key offers complete and permanent access to your account and all the funds involved. 

    ➢ Your private key is extremely valuable, so it is encrypted with a master key.

    ➢ For security purpose, this encrypted key is encrypted again with a key generated from the Android of your device or a secure area if you are using and IOS device.

    ***Quantification:***
    ➢ MEW Wallet offers a PIN Code and a Biometric signature like a Face ID or a fingerprint 

   ➢ It uses another software called “Aave” with the MEW wallet app. 

   ➢ MEW wallet utilizes multi-layer encryption and isolation to keep your keys safely stored away locally in your device. 

   ➢ No one has access to these keys except you.

   ➢ The MEW Wallet app offers a 24- word recovery phrase to back up and restore your wallet. 

   ➢ This phrase acts the same as private key, so it is very important to write down on a piece of paper and stored it in a different area.

4. **StrongCoin.** It is a hybrid wallet that allows you to send and receive bitcoins just like any other wallet. The bitcoin private key which requires you to send money is encrypted in the user browser before reaching out to their servers. Therefore, their servers only hold encrypted private keys and you are the only one that can spend your bitcoins. Even non hybrid wallets are not safe; It would only take a hacker or an employee to have access to your keys and all your bitcoins will vanish forever. Nevertheless, experienced bitcoins users can lose their coins because they can mistakenly delete their wallet file on their computer. So, StrongCoin can take care of offsite secure backup so you do not have to worry as much.

    **Table 2**
*Pros and Cons on StrongCoin Table*
    ![Pros and Cons on StrongCoin Table](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-table-2.png)

    ***Identification:***
    ➢ Offline paper backup like USB flask disks. 

    ➢ Keroku security to ensure transparency in its security promise and a reputable cloud perform known to perform regular security audits. 

    ➢ StrongCoin built-in escrow service helps protect your trading engagements when buying and selling. 

    ➢ Private keys are what allow users to gain access to their cryptocurrency funds, meaning that they should be kept secure from others. 

    ➢ Buy Bitcoin directly

    ***Quantification:***

    ➢ You have a public key that you can send and receive money.

    ➢ You have control of your private keys.

    ➢ It works on multiple devices like desktops, tablets, mobile devices (Android and IO’s)

    ➢ It only offers hybrid wallet.

5. **Jaxx.** It is another cross-platform blockchain wallet which managed bitcoin, Ethereum and many cryptocurrencies. It is a simple process to send and receive many cryptocurrencies in your wallet; one can view their balance, any transaction, and detailed coin information. Furthermore, It does connect easily to third-party trading services. The third-party trading is mostly Changelly and Shapeshift that can have access to your wallet. You can buy and sell any supported digital assets which includes bitcoin, Ethereum and Litecoin. As for the security purpose, you are the one owning the keys which means that it is a twelve-word phrase mnemonic, generated by using a standard BIP 39 libraries. To further secure your Jaxx wallet, you will need a longer password combing numbers, special characters, upper- and lower-case letters. To protect the data, you must take extra security measures by encrypting core wallet data using a bank grade encryption after setting up a password.

    Below are the steps on how to download Jaxx though your desktop, Chrome Extension, or mobile devices IO’s and Android (Yasin, 2018).

    **Figure 7**
*Downloading Jaxx (Yasin, 2018)*
    ![Downloading Jaxx (Yasin, 2018)](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-fig-7.png)

    **Figure 8**
*Creating a Checksum for Every Download (Yasin, 2018)*
    ![Creating a Checksum for Every Download (Yasin, 2018)](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-fig-8.png)

    **Figure 9**
*Latest Features on the Application (Yasin, 2018)*
    ![Latest Features on the Application (Yasin, 2018)](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-fig-9.png)

    **Figure 10**
*Create a New Wallet or Restore an Older One (Yasin, 2018)*
    ![Create a New Wallet or Restore an Older One (Yasin, 2018)](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-fig-10.png)

    **Figure 11**
*Two Options: Express or Custom on Jaxx (Yasin, 2018)*
    ![Two Options: Express or Custom on Jaxx (Yasin, 2018)](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-fig-11.png)

    **Figure 12**
*Selection of Cryptocurrencies on Jaxx (Yasin, 2018)*
    ![Selection of Cryptocurrencies on Jaxx (Yasin, 2018)](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-fig-12.png)


    **Figure 13**
*Fiat Currency on Jaxx (Yasin, 2018)*
    ![Fiat Currency on Jaxx (Yasin, 2018)](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-fig-13.png)

    **Figure 14**
*Backup Phrase of Jaxx (Yasin, 2018)*
    ![Backup Phrase of Jaxx (Yasin, 2018)](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-fig-14.png)

    **Figure 15**
*Set Up 4-digit Security Pin (Yasin, 2018)*
    ![Set Up 4-digit Security Pin (Yasin, 2018)](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-fig-15.png)

    ***Identification:***

    ➢ Jaxx has both password and PIN protection. 

    ➢ Jaxx never has access to that phrase or your private keys, they are always securely on your own personal device. 

    ➢ There is an improved new security model that protects your sensitive information with a strong password, while using an AES-256 encryption enhanced by 5000 rounds of PBKDF2 password hashing. 

    ➢ It has anonymous tracking, recovery seed, Password protection, automated updates. 

    ➢ A hierarchical deterministic wallet is a wallet whose design allows to create different unplanned addresses for different transactions. It indicates that every time you transact with the Jaxx wallet, it will generate a random public key.

    ***Quantification:***
    ➢ Backup wallet where you can find your unique 12-word backup phrase and pairing code and have the option to back up your wallet by verifying the backup phrase. 

    ➢ Display private keys by viewing and exporting and public address. 

    ➢ Pair devices from another device with your backup phrase or pairing code 

    ➢ You can Transfer paper wallet, Setting up the security PIN. 

    ➢ Reset Jaxx cache by clearing cached data and BTC mining fees.

6. **CoinWallet.** It is one of the easiest wallets, similar like Coinbase to buy, sell and hold cryptocurrencies. You can connect to many banks to transfer money in and out of the wallet. You can even use that money to buy bitcoin and any further cryptocurrency. All your digital assets such as tokens and collectibles are stored in one place on your own device. For security purposes, your keys are protected with secure enclave and biometric authentication technology. You will need a password and an email account to be able to access and send message from that email address. Wallets have what is called a private key that is needed to send funds from a digital wallet. You are the one managing your private keys most of the time, securing your funds with a password, device confirmation, and 2-factor authentication. They will then utilize this secure cold storage technology to protect customers’ funds.

    ***Identification:***
    ➢ The 2-step verification feature can also be enabled in our account’s settings while using biometric fingerprints.

    ➢ You are recommended to enable a security passcode in the app’s security settings. 

    ➢ It is important to secure your email and your Coin Wallet / Coinbase account 

    ➢ Security keys and Time-based One Time Password (TOTP) can both be enabled in your account’s settings.

    ➢ Keep your devices clean and updated by utilizing anti-virus protection and scan your device regularly. 

    ➢ Protect your cloud storage accounts while utilizing the address book and whitelisting features.

    ➢ Whitelisting is a security feature in the address book that allows Crypto withdrawals to only go to addresses already designated in your address book.

    ***Quantification:***
    ➢ Use a strong, long, random, and unique password for your account. 

    ➢ Utilize the strongest form of 2- step verification for all cryptocurrency transactions. 

    ➢ Recurring transactions are an interesting function. 

    ➢ It provides simple way to buy and sell the most popular Cryptocurrencies such as Bitcoin, Ethereum and Litecoin 

    ➢ You can purchase Cryptocurrency via credit or debit card, a wire or bank transfer. 

    ➢ Setting up an account is a quick and easy process, it requires your full name, address, bank details and proof of ID.

7. **Green Address.** It is a handy wallet with multi-signature, enhancing security feature, and privacy; this wallet enables users to access, store, send or receive bitcoin alone. But users can access their wallet through their mobile phone or the web. It does have good security features to ensure the safety of the users’ funds. It does support twelve languages, and the wallet app is available for download in specific app stores such as Android and IOs stores. For security measures, your keys are not directly sent to you, not even the servers and encrypted form contain them. However, logging in the app will require you to input your mnemonic phrase and password. Eventually, you will need to access the app with a PIN number. With this feature, you can check your wallet balance anytime, or conduct any transactions without full access to the wallet. The article on “Review Green address Bitcoin wallet” mentioned that the Green Address has some advantages and disadvantages that users should be aware which are listed below (Ryan, 2018).

    Advantages:
    ➢ Several security tools availability with four different options on the two factors authentication

    ➢ Multi-signature of wallets

    ➢ API tools availability to use.

    ➢ Mobile platforms availabilities

    ➢ Four fee programs availabilities

    Disadvantages:
    ➢ Recovery phrase and PIN code are created by the server.

    ➢ Only Bitcoins are supported by the platform

    ***Identification:***
    ➢ Provide pre-signed transaction which means that each time your wallet has updates we will forward to you by unlocking funds at a date in the future of your choice. 

    ➢ Offering a second signature that provides extra security with two factor authentications for transacting, transaction limit, and instant payments with double protection.

    ***Quantification:***
    ➢ PIN login to your wallet from any of your devices without using passphrase.

    ➢ Generated recovery passphrase and PIN codes and setting up the two-factor authentication through your phone number. 

    ➢ The two factors have four options which are google authenticator, phone call, email, and SMS. 

    ➢ They are very organized properly, all the buttons are visible, and the navigation through the wallet is extremely convenient for beginners in the Crypto industry.

***Hardware Wallets***
1. **Trezor T.** It is a hardware wallet that allows you to send, receive, and store a wide range of cryptocurrencies; It is also much safer than any traditional software wallets in which your private keys are held on the physical device instead of a desktop or a smartphone. It is never connected to an internet server, meaning that hackers cannot have access to your funds. It is one of the multi-currency wallets in which one can store a plethora of cryptocurrencies. It does have some advantages and disadvantages which are listed below.

    **Table 3**
*Trezor T Wallet Advantages and Disadvantages*
    ![Trezor T Wallet Advantages and Disadvantages](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-table-3.png)
    
    For security overview, the wallet has something called “limited USB Connection” which means that even if the computer device is infected, your cryptocurrency would still be safe. The Trezor team has designed another way for the PIN number like every time you enter a number, the setup of the numbers changes automatically. That is the way to avoid your PIN getting compromised by hackers. The article titled “An in-Depth look at the Trezor Model T hardware wallet “ stated how to set up or install the device with specific instruction to follow while going to Trezor website to initiate the wallet or the firmware, creating a new wallet, backing up the seed, adding a PIN and naming the wallet (Redman, 2019).

    **Figure 16**
*Initiate the Firmware, Create a New Wallet and Backing Up the Seed (Redman, 2019)*
    ![Initiate the Firmware, Create a New Wallet and Backing Up the Seed (Redman, 2019)](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-fig-16.png)

    **Figure 17**
*Setting Up the PIN and Naming the Device (Redman, 2019)*
    ![Setting Up the PIN and Naming the Device (Redman, 2019)](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-fig-17.png)

    ***Identification:***
    ➢ PIN is a powerful tool to keep your coins safe. 
    
    ➢ Passwords on the device are individually locked with Trezor password managers employ a user’s digital keys. 
    
    ➢ Creating the standard recovery seed which enables users to recover the entire wallet with the help of a twelve-word recovery seed.
    
    ➢ Contains a passphrase to generate a new wallet; users will be required to enter the passphrase in addition to their security PIN.

    ***Quantification:***
    ➢ It is protected by a PIN code which can be up to nine digits long.
    
    ➢ You Keep your recovery seed safe.
    
    ➢ You can reinforce your accounts with U2F hardware.
    
    ➢ It is compatible with both computers and smartphones software’s such as windows 10. MAC operating systems, Linux, and Android Operating systems

2. **Ledger Nano X.** It is another hardware wallet that allows you to buy and securely manage your crypto in one single-app, everywhere you go. You connect your device to the ledger live mobile app with Bluetooth and safely manage your crypto from your smartphone. For security measures, when owning crypto, you only get your private key. You need to secure it to secure your funds. It does offer the best level of protection in which your keys will remains protected in a certified secure chip. It does support 1500+ crypto assets, helping you in managing any transaction (Figure 18, shown below).

    **Figure 18**
*Ledger Nano X (Phillips & Phillips, 2020)*
    ![Ledger Nano X (Phillips & Phillips, 2020)](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-fig-18.png)

    It does come inside a small package that includes the device itself, a USB cable, one keychain, a kay ring, and multiple recovery sheets to write down your seed phrase provided.

    ***Identification:***
    ➢ You can set up the PIN protection that the end user must enter correctly before accessing all services provided by Ledger Nano X 
    
    ➢ Ledger Nano X does not keep backup of your recovery phrase. 
    
    ➢ Make sure you are the one holding your 24 words recovery phrase.

    ***Quantification:***
    ➢ You can Set up a PIN code on your device with 8 digits for optimal security.
    
    ➢ Set up a password with 4 numbers to prevent unauthorized access ledger data on your phone.
    
    ➢ You can set up the software on your IO’s, Android and computer
    
    ➢ It does support most languages and you can select the one you prefer.

3. **Keepkey.** It is a hardware wallet making the bitcoin security even more simple for users; It does provide users or investors with a secure environment to store their cryptocurrency wallets such as Bitcoin, Ethereum, Litecoin, Name Coin, and Dash. As for security, keepkey stores your private keys in a separate offline environment. In addition, the keepkey can be protected by using the PIN code and backed up with an eighteen to twenty-four-word recovery seeds. It does have several randomizations to prevent hackers from stealing your digital assets with malware.

    ***Identification:***
    ➢ The private key is stored directly on Keepkey and it does not leave the device.
    
    ➢ Your PIN code prevents any hackers from having access or viewing any transactions or your balances. 
    
    ➢ The keepkey wallet is entirely backed up with a 12-word recovery sentence that is generated on setup. It can also be used to recover in case if you lose your wallet or it gets stolen. 
    
    ➢ You can have the convenience of accessing and trading cryptocurrency directly from your wallet.

    ***Quantification:***
    ➢ The keepkey is very flexible and it can be used in different types of operating systems devices such as Windows, MAC OS, Linux, Android, and Chrome extension 
    
    ➢ All private and public keys must be secured with an authorized PIN Code which you will have access every time.

    The keepkey wallet does have some advantages and disadvantages that needs to be taken into consideration.

    Advantages:
    • The level of security of the Keepkey wallet is very high because the hardware wallets are impossible to get hack or concede.
    • The wallet has a built-in exchange with other cryptocurrencies wallets for further ease of use and functionality for investors.
    • The Keepkey wallet can manage multiple cryptocurrencies.
    • You will need a randomized PIN number to unlock the wallet.

    Disadvantages:
    • If you leave your device or computer without you being in front and someone else have access to your device, you can lose all your information on your device.
    • The keepkey wallet is very expensive to purchase because of the quality of the wallet.

4. **Bitbox.** It is a simple minimalist hardware wallet which secure your digital assets and manages them easily. Moreover, it does support Bitcoin, Ethereum, and Litecoin. For security purpose, it does have a private key stored on an ultra-secure tamper-proof chip: the password is encrypted; malware proof meaning private keys never touch the internet or external device; easy backup and recovery; unified accounts; full node support; encryption communication and open- source auditability.

    ***Identification:***
    ➢ It has an easy backup thanks to a microSD card and can display your 24 recovery words. 
    
    ➢ It is important to securely verify your transactions by receiving addresses and other data while entering your password directly on the OS device instead of the app itself.
    
    ➢ A secure chip is important to avoid any brute force attacks by using your password which will make such attacks even more difficult to access it

    ***Quantification:***
➢ You will need to set up a name and password for the wallet. 

➢ Each device’s password encrypts the backup of the wallet and is generated with the password; if in case you change your password in the future, the device password will no longer be recognized or will no corresponds to the recovery passwords of older backups. 

➢ You will need to set up your password which consists at least four characters.

5. **ColdCard.** it is an easy wallet to use, extra secure, open source and very affordable hardware wallet. It is easy to backup with an encrypted microSD card. You have full control over your bitcoins, meaning that no third party can freeze, or have access to your funds. You are responsible for securing and backing up your wallet. Your private keys are stored in a dedicated security chip. They used the software called Micro Python to make changes. For security purposes, the wallet is loaded from a secure specialized environment provided by the device. It does provide a very strong protection against computer vulnerabilities and malware.

    ***Identification:***
    ➢ It only supports Bitcoin and Litecoin cryptocurrencies. 
    
    ➢ Verification of the device serial number to ensure that it matches the serial number on the package. 
    
    ➢ You are only recommended 4 to 6 digits while entering the prefix PIN to protect against hackers. 
    
    ➢ You will need to enter the rest of your preferrable PIN with only 4 to 6 digits. 
    
    ➢ It supports a passphrase of 24-word seed in which you will access to a new wallet for any passphrase.

    ***Quantification:***
    ➢ The PIN code for Coldcard can be from 4 to 12 digits long which can be divided into two parts: the prefix and the rest PIN. 
    
    ➢ The Coldcard can store the private key in a secure element that will encrypt the data SHA 256 hashing and a true random number generator.
    
    ➢ You can also import the existing wallet by providing 12-to-24-word seed for the Coldcard. 
    
    ➢ It also uses a microchip to store important information.

***App-based Wallets***
1. **Coinbase.** The number one mobile app, crypto wallet app, and web3 Dapp browser. It makes it easy for users to send, receive, and store bitcoin, Ethereum, Litecoin and Bitcoin Cash. It allows users to interact with the web3 decentralized application powered by Ethereum. The capabilities of Coinbase are:

    ➢ Security of the user-controlled crypto wallet, meaning sending, receiving, securing, and storing; you are in control of your private keys which are stored only on your devices using secure element technology. You only have access to your funds, nobody else. 

    ➢ You can send cryptocurrency payment to anyone all over the world. It does have a backup private key to the cloud, meaning you backup your wallet and private keys to Google drive to prevent yourself from losing your funds, your device, or misplacing your recovery phrase.

    Coinbase is very safe and has been used in more than 30 States in the United States and many countries in which you can send and receive funds, can store users’ digital assets in an offline storage, and the cryptocurrency is stored on the user’s servers with protection.

    ***Identification and Quantification:***
    ➢ You can manage your portfolio by buying and selling digital currencies, keeping track of all of them. 
    
    ➢ You can invest in cryptocurrency by scheduling a day you want to buy if it is daily, weekly, or monthly. 
    
    ➢ You can use the Coinbase app on Android and IOS. 
    
    ➢ In addition to the verification on all accounts, you will need a username, password while entering a code provided by the mobile phone and adding more security to the account. 
    
    ➢ You can add security by storing your funds in a vault even if it shows any delayed withdrawals. 
    
    ➢ It is beginner friendly and easy to use with clear tools, great information and details on different cryptocurrencies wallets. 
    
    ➢ It accepts a variety of payment methods and fiat when it comes to the money to buy Crypto through bank transfers like debit/ credit card. 
    
    ➢ You will need a strong password very long, must be random and unique. 
    
    ➢ To protect your mobile devices, you should use anti-virus protection and a scanner for your device. 
    
    ➢ To prevent any threat, you can ensure that your digital assets are in a safe place by stopping the most advanced malware, scammers, and ransomware. 
    
    ➢ Be very aware of phishing so that they will not have access to your information (debit card, credit card, and password).
    
    ➢ Coinbase is a very safe application that ensure that your account and cryptocurrency are in a safe place.

2. **Electrum.** It is a fast, secure, and easy to use wallet and furthermore, it is one of the most popular bitcoin wallets on the market. It does split the permission to spend your bitcoin between several wallets. It also supports hardware wallets like Ledger, Trezor and Keepkey. It has various user interfaces which can be used on mobile, and desktop. It is a free software; it is decentralized, and anyone can run an electrum server.

    They are two factor authentication which are being safe from malware, using two factor authentications by electrum and trusted coin, which you can only verify. It does have a private encryption key using a seed containing twelve to twenty-four words, with a strength between 128 bits and 256 bits, making it difficult to crack. A seed phrase is also a recovery tool in which if you forgot your password, the seed phrase is the only way to bring your wallet back (Bogdan, 2018).

    ***Identification:***
    ➢ You will need to trust the Electrum lead developer since it was created in 2011. 
    
    ➢ You can connect to a trusted server by letting Electrum decide which server to use the option to take. 
    
    ➢ You will receive a 12 words of generations seed which will allow you to recover your wallet in case your computer crashes.
    
    ➢ You can create a password with a maximum of 6 to 8 characters to encrypt your wallet’s keys. 
    
    ➢ All the investor’s funds are swept from a paper wallet or transferred into the Electrum wallet while importing the private keys. 
    
    ➢ Electrum’s seed allows you to rebuild all of your wallet ‘s addresses and private keys. 
    
    ➢ Backups of Electrum are very easy to first create, secondly, manage and thirdly provide great security.

    ***Quantification:***
    ➢ It uses a remote server that can perform the most complicated tasks and allows you to restore your wallet easily and your passwords. 
    
    ➢ It does have a private key with a 128-bit base value, meaning that investors do not need any backups.

    The fact that Electrum does support a few cryptocurrency wallets like Bitcoin cash, Litecoin and DASH, however, it does have some advantages and disadvantages that should be considered:

    Advantages:

    • The operation speed of the Electrum is very important.
    • It is very simple to use the app.
    • It has a very safe systems which provides investors with control over their funds.

    Disadvantage:

    • There is an inability to generate the Nested Setwig addresses due to insufficient compatibility with every services.

3. **Blockchain.** It is a very safe, easy to use and supports a wide range of currencies. It uses a twelve words backup phrase to protect your wallet; acting as a backup to ensure access to your funds. Your wallet private keys never leave your possession, and you only have access to your wallet. You can backup when you needed too while blockchain creates a server-side backup by using a strong encryption. For security feature, you include a PIN protection, paper wallets import as well as submitting the wallet code for security audits.

    ***Identification:***
    ➢ Blockchain security feature contains records of transactions of any digital assets between two different parties. 
    
    ➢ Security aspects can be very critical while focusing on transparency, confidentiality and protection against hackers and fraudsters. 
    
    ➢ Blockchain offer confidentiality by enabling investors with a ledger to see only the authorized transaction. 
    
    ➢ It also helps prevent malicious attacks.
    
    ➢ Investors have their own private and public keys most precisely for the transactions they make and their account for their personal signature. 
    
    ➢ The public key blockchain uses computers to connect to the public internet in which any computers can obtain access and join.
    
    ➢ As for the private key blockchain, only members who have their own identity registered can join.

    ***Quantification:***
    ➢ Solidity is used to build and deploy smart contracts on any blockchain and Ethereum based applications. 
    
    ➢ Geth is a program which acts as a support of the Ethereum blockchain and allows investor to transfer tokens between addresses, create, and execute smart contract through the Ethereum virtual machine, and explore block history on blockchain. 
    
    ➢ Remix does support deployment, testing and debugging of smart contracts that connect to the blockchain while using MetaMask. 
    
    ➢ “My Ether wallet”, the safest way to store Cryptocurrency is by using a paper wallet that has two ways of storing; namely hot and cold storage; hot storage makes it easy to spend Crypto as it is connected to the internet but can be vulnerable to hackers; cold storage which stored the cryptocurrencies offline is very difficult to spend but is very safe from attackers.

    The benefits of Blockchain are as follows:
    • It has a great transparency with blockchain technology.
    • It enhances security better than any other record keeping systems.
    • It eliminates error through real- time tracking of transactions.
    • It improves traceability.
    • It increases efficiency and velocity, but reduces on- cost, and material cost.

4. **Robinhood.** Robinhood did not start as a crypto wallet but is a free-trading app that lets investors trade stocks, options, exchange-traded funds, and cryptocurrency without paying commissions or fees. It does offers both web and mobile trading, but the platforms are purposely bare-boned, and some investors may find the range of tradable securities and account options lacking. The positive aspects of Robinhood are that you can trade and exchange cryptocurrencies in an easy manner. Its target audience are first time traders and cryptocurrency investors to whom they charge annual fees and account fees.

    It is very beneficial for those are constantly trading their crypto Coins. In other words, the Robinhood wallet will suit short-term traders the best to perform trades very quickly and effectively, while avoiding the possibility of missing out on a potential deal. A key benefit that one will notice is that Robinhood’s crypto wallets support all sort of main cryptocurrencies like Bitcoin, Bitcoin Cash, Ethereum classic, Litecoin, and Dogecoin. It is super easy to use, beginner friendly when it comes to cryptocurrency choices, and its usability aspects (Carey, 2020).

    As for the advanced security features with online wallets, especially those that are based in exchanges have a hard time when it comes to persuading the user that their crypto coins are secure while being in the wallet in- question.

    When it comes to discussing Robinhood’s Crypto wallets with respect to security, you’d have the ability to turn on two-factor authentication, while also being able to add some custom PIN codes in order to ensure even better standards of protection.

    The negative aspects when it comes to using Robinhood’s Crypto wallets is that it does come with a lot of issues on the security side of things; It does have a potentially unsecure cryptocurrency wallet when it comes to online, software(app), hardware, and paper wallet in the order of the least secure to the safest one. Robinhood crypto wallet is an online based exchange platform because it is always connected to the internet in which can always be hacked or stolen during a cyberattack. It does not have any retirement account, no mutual funds or bonds, and has limited customer support.

    ***Identification:***
    ➢ You have a sensitive details and information present there, for instance your Social Security Number which is encrypted before they are stored on the app. 
    
    ➢ Your account password is not stored on the plaintext but hashed while using the BCrypt hashing algorithm. 
    
    ➢ Your mobile phone and the web application communicate with the servers while using the Transport Layer security. 
    
    ➢ It does not have any access to your banking verification after it is processed; they do however use trusties third party to access the investor’s information on their bank account such as your account balance. 
    
    ➢ You can secure your mobile app by using a Face ID, a PIN code with a fourdigit number, and touch ID.

    ***Quantification:***
    ➢ It offers market news where you can browse to see news articles on financial posts, Reuters, New York Times, and MarketWatch.
    
    ➢ It provides top movers which shows which stocks are moving the most.
    
    ➢ You can create a customized list of stocks you would like to follow.
    
    ➢ You can use analyst ratings to help you decide on what you need to buy, hold, or sell.
    
    ➢ The candlesticks chart helps you to analyze trends in a stock performance.
    
    ➢ Margin trading allows investors to control their buying power.
    
    ➢ The stock screeners which scan the whole market by providing averages on the price, trading volume, charting patterns and allows investors to compare different options.

5. **Exodus.** It is a secure, wonderful desktop bitcoin and cryptocurrency wallet. What makes it different from other wallets is that it focuses on user experience; it provides information on your crypto assets and makes it easy to trade cryptocurrencies. It does provide the information you need and makes it easy to find what you are exactly looking for. It does not have a hosted centralized server. You are in control of your cryptocurrencies meaning your own security guard; you keep your private keys on your computer. It is also available on Android and IOs devices and supports twelve words seed phrase.

    ***Identification:***
    ➢ Setting up a password on Exodus wallet is important and must be a unique password with at least 16 characters long to prevent hackers from gaining access or using malware. 
    
    ➢ They used hardware wallets to enhance security while pairing it with Trezor.
    
    ➢ In case of funds lost in the Exodus Wallet, you are required to send the remaining funds to a different wallet, and a wallet Safe report. 
    
    ➢ It is important to protect your secret twelve words recovery phase. 
    
    ➢ It is important that you do not download any suspicious sites or pirates’ sources.

    ***Quantification:***
➢ You can use the Exodus Wallet on multiple devices such as Android, IOS, and computers if each app is on the latest version. 

➢ After downloading the Exodus wallet app on the current computer, you will need to find the 12-word secret phrase and restore it into your new computer device.

6. **Mycelium.** It is one of the oldest and most popular bitcoin wallets available. It is accessible, you can send and receive bitcoin anywhere in the world and at any time. You can even pay for goods and services, receive funds from others quickly and easily with the QR code embedded right on the front page of the wallet. It allows you to change settings to your preferences.

    As for security feature, Mycelium wallet has the expected PIN protection for opening the wallet, sending funds, and exporting private keys. It does have a backup seed phrase of twelve random words when you generate your wallet. The seed phrase can be used to restore your wallet on a different device if needed.

    ***Identification:***
    ➢ Blockchain application is one of the main security considerations for this wallet. 
    
    ➢ it has a PIN protection for having access to the wallet, sending funds, and exporting the private keys. 
    
    ➢ you get a backup seed of twelve random words which can be used to restore another wallet if needed. 
    
    ➢ you can monitor your funds or balances without exposing your private keys to anyone. 
    
    ➢ Mycelium does a great job on maintaining the security of your Bitcoin when it comes to the smartphone app.

    ***Quantification:***
    ➢ it is one of the oldest Bitcoin wallets used on Android and iOS devices.
    
    ➢ Mycelium wallet is very accessible meaning you can send and receive Bitcoin anywhere.

7. **CashApp.** It is a mobile payment service created by Square. Inc., very easy to download on devices such as iOS and an Android and allows users to send or receive money from another user using the mobile App as well. It allows you to request, and transfer money to another cash account which runs like a virtual bank platform. You can withdraw the money with their ATM card called the Cash Card, which is a black customizable Card, which makes investing in Cryptocurrency even more convenient.

    ***Identification:***
    ➢ It does have security features such as PIN entry, Touch ID, or Face ID verification protected payments. 
    
    ➢ It does have limited Cryptocurrency Wallets and your Bitcoins are securely stored in an offline system. 
    
    ➢ You will receive an account notification alert on your email. 
    
    ➢ They protect all your data by using the PCI-DSS level 1 certification. 
    
    ➢ You have protection on unauthorized charges.

    ***Quantification:***
    ➢ It is used on smartphone devices devices using both Android and iOS operating systems.
    
    ➢ They will help you create a unique username called a “$” cashtag which allows users to transfer and request money from one-another after entering this username.
    
    ➢ It does not charge monthly fees.
    
    ➢ You can invest or buy stocks in specific companies with few restrictions on the scale of purchase.
    
    ➢ There are fees while using Credit or Debit Cards from elsewhere, CashApp will charge of 3% of those transactions in order to complete.

***Paper Wallets***
The safest way to store any cryptocurrency is by using a paper wallet. It is an offline cold storage method of saving cryptocurrency. It includes printing out your public and private keys on a piece of paper which you store and save in a secure place. The keys are printed in the form of QR codes which you can scan in the future for all your transactions.

The reason why it is so safe is that it gives complete control to the user. You do not need to worry about the well-being of a piece of hardware, nor do you have to worry about hackers or any piece of malware. This makes you the master of your investment, and if following the instructions are followed properly, there is a little chance of your private keys falling into someone else’s hands; of course, this means that keeping a record of them is even more important. Losing private keys means you will lose the entire contents of your paper wallet.

### Data Analysis
A data analysis is a set comprised of information that uses qualitative and quantitative data to analyze as well as to evaluate and compare different types of cryptocurrency’s wallets but mostly be focused on three cryptocurrency wallets that I am currently using on my device which are Robinhood, CashApp and Coinbase. Below is the procedure used to analyze the data.

**Figure 19**
*Data Analysis of Different Cryptocurrency Wallets*
![Data Analysis of Different Cryptocurrency Wallets](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-fig-19.png)


**Figure 20**
*Percentages of Different Cryptocurrency Wallets*
![Percentages of Different Cryptocurrency Wallets](https://statics.bsafes.com/images/papers/evaluating-security-in-cryptocurrency-wallets-fig-20.png)

According to the statistics, the three most popular platforms that I am currently using, and most traders and individuals are using nowadays are, Rohinhood, Coinbase Wallet, and CashApp; when comparing the three cryptocurrency wallets, they are very easy to use but have some slightly differences. Robinhood is a free trading application that allows traders or investors to trade free stocks, options, cryptocurrencies, exchange trading funds without paying any fees. It does offer web, individual taxable accounts, margin accounts, cryptocurrency, and mobile trading.

The mobile trading platforms offers customizable alerts, candlesticks charts, news, and ability to listen to live to earning calls. Robinhood also puts limits on orders on all transactions of the traders so they do not perform if the market moves against them after an order is placed. It makes transactions quite a lot easier by showing a trading price without fees. Unfortunately, having no fees causes a huge mark-up in which other orders and trade prices are not showed. Robinhood only offers a limited range of 7 stocks for trading. If you plan on using the US Dollar for your trading, Robinhood is the best choice for you.

If you want to use your funds with bitcoin or buy bitcoin and transfer it to a private controlled wallet or a different trading platform, Coinbase wallet would work best for you as It has both a convenient layout and software with online wallets which gives access to a wide spectrum of decentralized innovation in which allows users to store their own Crypto. You do not really need to create a Coinbase account to use the Coinbase Wallet app. It helps users to manage their own private keys by storing their Crypto assets on their devices. There is also a fee schedule posted on their website depending on how much you trade, which can be difficult to calculate the net trading price. Coinbase offers more than17 stocks for trading as well. If you are looking to only invest in the future of currency, which is digital Coinbase remains the easiest place to buy, sell, and manage your digital currency.

The last one is CashApp, owned by Squares. Inc., it is a financial technology industry leader and one of the largest payments transfer application wherein users can send and receive money. But the App is also used to invest in stocks, as well as to buy and sell Bitcoin; it has been increasing immensely in popularity since the year of 2020 due to the pandemic or COVID-19 pandemic situation with the percentage of 127% in the quarterly revenue, and a 361% increase year-on-year.

Furthermore, it functions very similar to a bank account, giving users a debit card called “cash card” to make purchases using their funds in their cash app account even easier. CashApp does not charge any fees when sending and receiving money. However, if you are using a credit card, there is a fee of 3% on the transaction to send money. But to avoid being charged, it would be better to link your bank account and deposit the money in the next 2 or 3 days maximum. CashApp does have a limited stock and can start as a little as a one-dollar purchase, however, they do allow you to invest in partial shares which is a good way to build a portfolio with a small amount of cash.

### Summary
After identifying, quantifying, analyzing, and evaluating the Cryptocurrencies wallets such as web-based wallets, App- based wallets, hardware wallets, we conclude that they do possess different types of security features and privacy that are very important. To secure the cryptocurrencies wallets, you can either convert to paper wallet by following their instructions on bitcoinpaperwallet.com or using a cold storage for a safe place. The last chapter would be focus on the results, the conclusions, and the future work on how to evaluate security in Cryptocurrency wallets.

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/cryptocurrency/evaluating-security-in-cryptocurrency-wallets-1/">Chapter I - Introduction</a></li><li> <a href="/docs/cryptocurrency/evaluating-security-in-cryptocurrency-wallets-2/">Chapter II - Background and Review of Literature</a></li><li> <a href="/docs/cryptocurrency/evaluating-security-in-cryptocurrency-wallets-3/">Chapter III - Methodology</a></li><li> <a href="/docs/cryptocurrency/evaluating-security-in-cryptocurrency-wallets-4/">Chapter IV - Data Presentation and Analysis</a></li><li> <a href="/docs/cryptocurrency/evaluating-security-in-cryptocurrency-wallets-5/">Chapter V - Results, Conclusion, and Recommendations</a></li><li> <a href="/docs/cryptocurrency/evaluating-security-in-cryptocurrency-wallets-6/">References</a></li></ul>

***

</div>
