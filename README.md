<!-- vscode-markdown-toc -->
* 1. [Table of Contents](#TableofContents)
* 2. [Foundation for Development](#FoundationforDevelopment)
	* 2.1. [The Inception of PAL Companion](#TheInceptionofPALCompanion)
* 3. [What is this app for?](#Whatisthisappfor)
	* 3.1. [**Efficient inventory management made easy**](#Efficientinventorymanagementmadeeasy)
* 4. [Getting Started](#GettingStarted)
	* 4.1. [Download instructions](#Downloadinstructions)
	* 4.2. [Profile setup and login](#Profilesetupandlogin)
* 5. [Features and Usage](#FeaturesandUsage)
	* 5.1. [Start an inventory database](#Startaninventorydatabase)
	* 5.2. [Command syntax and functionality](#Commandsyntaxandfunctionality)
	* 5.3. [Command usage variations <br> <sub>Exploring different scenarios</sub>](#CommandusagevariationsbrsubExploringdifferentscenariossub)
		* 5.3.1. [🎨 create](#create)
		* 5.3.2. [🎨 show](#show)
		* 5.3.3. [🎨 list](#list)
		* 5.3.4. [🎨 filter](#filter)
		* 5.3.5. [🎨 update](#update)
		* 5.3.6. [🎨 delete](#delete)
		* 5.3.7. [🎨 new cart](#newcart)
		* 5.3.8. [🎨 add to cart](#addtocart)
		* 5.3.9. [🎨 cancel](#cancel)
* 6. [Legal Disclaimer](#LegalDisclaimer)
* 7. [Feedback and Support](#FeedbackandSupport)

<!-- vscode-markdown-toc-config
	numbering=false
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc --># Privisec ArtaLog (PAL)

**Privisec ArtaLog ( _PAL_ )** is a revolutionary _CLI inventory management companion_ designed to provide a comprehensive and secure solution for cataloging and organizing art collections. With a strong emphasis on ***privacy*** and ***security***, PAL companion was created to meet the needs of individuals who value the protection of their art-related data and the efficient organization of their valuable assets. PAL combines the power of archiving with the artistry of organization, offering artists, collectors, and enthusiasts alike a centralized and structured experience that transforms the way art estates are managed.

---

##  1. <a name='TableofContents'></a>Table of Contents

    Introduction
    Table of contents
    Foundation for development
    About the app
    Getting started
        Download instructions
        Profile setup and login
    Features and usage
        Start an inventory database
        Command syntax and functionality
        Command Usage Variations:
              create
              show
              list
              filter
              update
              delete
              new cart
              add to cart
              cancel
    Legal disclaimer
    Feedback and support

---
##  2. <a name='FoundationforDevelopment'></a>Foundation for Development

###  2.1. <a name='TheInceptionofPALCompanion'></a>The Inception of PAL Companion

Privisec ArtaLog companion was initially conceived as a solution to the challenges faced by my dads, who are passionate art enthusiasts. Inspired by my one of my dads, a celebrated artist and illustrator known for his captivating fashion sketches from since the '70s, PAL is designed to simplify the management process for a collection of artwork. With overflowing bins of sketches in his studio and a rich archive of artworks from various established artists and friends, the need for an efficient inventory management system became evident.
<details>
<summary>Key Challenges Addressed</summary>

Managing a sizeable art collection can be a daunting task, but the <strong>PAL companion</strong> is here to help. We understand some of the specific challenges you may face, including:

- Keeping track of specific artworks and their relevant details within your archive.
- Determining the value of artworks for insurance purposes or potential sales.
- Protecting your collection from damage or deterioration by maintaining proper documentation.
- Overcoming limitations for loans, exhibitions, collaborations, or contributions to scholarly collections.
- Preserving the historical context of artworks for future generations and enhancing scholarly collections.
- Simplifying complexities in estate planning and ownership transfers through clear inventory documentation.

</details>
<br>

---
##  3. <a name='Whatisthisappfor'></a>What is this app for?

**Privisec Artalog** is the result of our commitment to providing an efficient inventory management system without the hefty price tag. It empowers you to document and track essential information for each artwork in your collection. From artists and titles to mediums, dimensions, descriptions, and even appraisal valuations, the _**PAL** companion_ covers it all.
We've also introduced the innovative "vendor cart" system, streamlining consignment arrangements. The vendor's cart allows consignees to build transactional orders for requested items, which are then submitted to you for approval. Set pricing outlines, specify commission structures, and define payment methods—all with ease and flexibility.

###  3.1. <a name='Efficientinventorymanagementmadeeasy'></a>**Efficient inventory management made easy**

PAL is here to revolutionize the way you manage your art collection. With the artistry of organization and the utmost focus on privacy and security, PAL offers a seamless and structured experience tailored to your needs. Say goodbye to the chaos of managing your art estate and say hello to effortless documentation, tracking, and organization.
Get ready to unleash the full potential of your art collection with the **Privisec ArtaLog** companion.

 ***"Welcome to a new era of art management excellence!"*** 

<br>

---
##  4. <a name='GettingStarted'></a>Getting Started

###  4.1. <a name='Downloadinstructions'></a>Download instructions

To install _**Privisec ArtaLog** companion_ on your local machine, follow these steps:</p>

1. Download and install the latest version of `privisec-artalog` from our official website or GitHub repository.

    ```sh
   $ git clone https://github.com/username/artalog.git
    ```

2. Open your terminal or command prompt and navigate to the directory where PAL is installed.

   ```sh
   $ cd artalog
   ```

3. Install the required dependencies using npm:

   ```sh
   $ npm install
   ```

4. Run the command `pal launch setup` to initialize the application and begin the user profile setup process.

   ```sh
   $ pal launch setup
   ```

###  4.2. <a name='Profilesetupandlogin'></a>Profile setup and login
Get started here with ***Privisec ArtaLog***.

1. Run this script to create a secure user profile.
   
    ```sh
    $ npm run create-profile 
    $ pal create profile
    $ pal profile init --username <your_username> --password <your_password>
    ```

   *Make sure to replace <your_username> with your desired username and <your_password> with a strong, unique password. 

2. Log in to your ***PAL companion*** account.
   
    ```
    $ pal run login
    ```

---

##  5. <a name='FeaturesandUsage'></a>Features and Usage

###  5.1. <a name='Startaninventorydatabase'></a>Start an inventory database

You will to create and engage your inventory database to store details from your collection. This script will help get you started:

```sh
$ pal build database --name < datatbase_name > --location < database_location >
```
<details>
<summary>💡 Suggestive Tip</summary>

- Replace `< database_name >` with the ***name*** you want to give to your art collection database 
- Replace `< database_location >` with the ***url path*** on your system where the database will be stored.

</details>
<br>

###  5.2. <a name='Commandsyntaxandfunctionality'></a>Command syntax and functionality

Privisec ArtaLog provides a set of commands to interact with your art collection database.  Here are some key commands and their functionalities:

- pal `create`: Add a new artwork to your collection with all relevant details.
- pal `show`: Display detailed information about a specific artwork in your collection.
- pal `list`: View a list of all artworks in your collection.
- pal `filter`: Filter artworks based on specific properties, such as artist, medium, or valuation.
- pal `update`: Modify the details of an existing artwork in your collection.
- pal `delete`: Remove an artwork from your collection.
- pal `new cart`: Start a new vendor cart for consignment arrangements.
- pal `add to cart`: Add artworks to your vendor cart for consignment purposes.
- pal `cancel`: Cancel an ongoing vendor cart and remove all items.

 <sub>💡 The above commands are just examples, and PAL offers many more features and functionalities.</sub><br>
 <sub>💡 Refer to the _Privisec ArtaLog documentation_ or use the `pal --help` command to explore all available commands and their usage.</sub>

<br>

```sh
# These are examples demonstrating the usage of the commands:

$ pal create --title "Mona Lisa" --artist "Leonardo da Vinci" --medium "Oil on panel" --year 1503
$ pal show --id 123456
$ pal list
$ pal filter --artist "Pablo Picasso"
$ pal update --id 789012 --medium "Acrylic on canvas"
$ pal delete --id 345678
$ pal new cart --vendor "Art Gallery XYZ"
$ pal add to cart --cartId 987654 --artworkId 123456
$ pal cancel --cartId 987654
```
###  5.3. <a name='CommandusagevariationsbrsubExploringdifferentscenariossub'></a>Command usage variations <br> <sub>Exploring different scenarios</sub> 

---

<!------------------- CREATE ------------------->
####  5.3.1. <a name='create'></a>🎨 create

<blockquote>

```sh
 # creates a new entry 

$ pal create --title "Innerspace" --artist "Glenn Tunstull" --date "2015" --medium "oil on canvas" --dimensions "40x30" --valuation "6,500" --description "Capturing circular motions of vibrant colors" --image "innerspace.jpg"
 
 # appends a new art object and its details to a specific archive-collection
```
</blockquote>

<!-------------------- SHOW --------------------->
####  5.3.2. <a name='show'></a>🎨 show

<blockquote>

```sh
# find and displays the details of "Foggy Morning" from the collection

$ pal show --title "Foggy Morning"
```
```sh
# shows the detail of an item with the id, "akILjH090J"  

$ pal show --id "akILjH090J"
```
</blockquote>

<!-------------------- LIST --------------------->
####  5.3.3. <a name='list'></a>🎨 list

<blockquote>

```sh
# a list of all pieces from a collection

$ pal list
```
</blockquote>

<!------------------- FILTER -------------------->
####  5.3.4. <a name='filter'></a>🎨 filter

<blockquote>

```sh
# scans the <collection> and return all artists 

$ pal filter --artist
```
```sh
# returns all works by the artist, "Gwen Tunstall"

$ pal filter --artist "Gwen Tunstall"
```
</blockquote>

<!------------------- UPDATE -------------------->

####  5.3.5. <a name='update'></a>🎨 update

<blockquote>

```shell
# adds property( medium: acrylic on canvas ) to artwork "Sunset Serenade"

$ pal update --title "Sunset Serenade" --medium "Acrylic on canvas"
```
</blockquote>

<!------------------- DELETE -------------------->

####  5.3.6. <a name='delete'></a>🎨 delete

<blockquote>

```sh
# permananently removes the artwork "Sunset Serenade" and its details

$ pal delete --title "Sunset Serenade"
```
</blockquote>

<!------------------ NEW CART ------------------->

####  5.3.7. <a name='newcart'></a>🎨 new cart


<blockquote>

```sh
# creates a brand new vendor cart and initiates a new consignment arrangement

$ pal new cart
```
</blockquote>

<!----------------- ADD TO CART ----------------->

####  5.3.8. <a name='addtocart'></a>🎨 add to cart

<blockquote>

```sh
# includes the artwork "Sunset Serenade" in the consignment order cart

$ pal add to cart --title "Sunset Serenade"
```
</blockquote>

<!------------------- CANCEL -------------------->

####  5.3.9. <a name='cancel'></a>🎨 cancel

<blockquote>

```sh
# cancels current cart, undoing any changes and discarding added items

$ pal cancel cart
```
</blockquote>

<br>

<sup>Please note that a lot of features in _PAL_ are still in beta. Your feedback is valuable to us as we continue to improve the application, fix issues, and add new features in future updates. _PAL_ is designed to be user-friendly and accessible to both tech-savvy users and beginners alike. With the perfect alignment of my dad's request and this assignment, _PAL_ emerged as a solution to alleviate the challenges and costs associated with managing and preserving art collections.</sup>

---
<!------------------------ LEGAL DISCLAIMER ------------------------>
##  6. <a name='LegalDisclaimer'></a>Legal Disclaimer

<sup><u>Please review the following:</u></sup>
<blockquote style="font-size: 11px;">
<p style="margin-bottom: -10px;font-size: 18px; font-weight: bold; color: goldenRod;">
<img src="assets/disclaimer-icon-dk.png" alt="A disclaimer icon">
D<span style="font-size: 13px;">ISCLAIMER</span></p></sup>

---

The use of Privisec ArtaLog, its features, and any actions taken based on the information provided by the application are at your own risk. Privisec ArtaLog and its contributors disclaim all liability for any direct, indirect, incidental, special, or consequential damages arising from the use or inability to use the application or any material provided within.<hr>

<span style="font-weight: bold; color: goldenRod;">⚠️</span>
PAL is designed to provide a convenient inventory management solution for artworks and does not provide any guarantees or warranties regarding the accuracy, completeness, or reliability of the information stored or processed by the application.

<span style="font-weight: bold; color: goldenRod;">⚠️</span>
PAL strongly recommends consulting with legal professionals experienced in contract law or consignment arrangements to ensure that any consignment agreements or transactions conducted through the application adequately protect the interests of all parties involved.

<span style="font-weight: bold; color: goldenRod;">⚠️</span>
PAL does not assume responsibility for any insecure transactions, losses, damages, theft, or incidents involving consigned goods, whether arising from negligence, breach of contract, or any other legal theory. Users of PAL are solely responsible for ensuring the security and proper handling of their consignment agreements, transactions, and any related assets.

<span style="font-weight: bold; color: goldenRod;">⚠️</span>
PAL does not offer provisions for resolving disputes between parties, including mediation or arbitration. Users are encouraged to seek independent legal advice to address any disputes or legal issues that may arise from consignment arrangements facilitated by the application.<hr>

By using PAL and its affiliations, you acknowledge and agree that the application and its contributors shall not be held liable for any claims, demands, damages, or losses, including but not limited to direct, indirect, incidental, special, or consequential damages, resulting from the use or reliance upon the application or any material provided within, even if advised of the possibility of such damages.

Please refer to the governing law of your jurisdiction that will apply in case of any legal issues arising from the use of PAL or consignment arrangements facilitated through the application.<br>

</blockquote><br>

---
<!----------------------- FEEDBACK & SUPPORT ----------------------->
##  7. <a name='FeedbackandSupport'></a>Feedback and Support
