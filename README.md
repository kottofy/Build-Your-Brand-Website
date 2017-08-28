# Building Your Brand Website

## SETUP
1.	Download as a ZIP or clone this repository onto your computer. 
2.	Open the folder in Visual Studio Code.

## BOOTSTRAP
Bootstrap is the most popular HTML, CSS, and JS framework for developing responsive, mobile first projects on the web. Let’s start with a basic Hello World template then build off it with components and code snippets to customize our own website.

3.	Right-click on the `index.html` file and select "Reveal in Explorer". 
4. Double-click or open the `index.html` file in a browser to view the current site.
5.	Try adding some of the following elements to your website from the [Bootstrap website](https://v4-alpha.getbootstrap.com/examples/).

| Feature  |  Type |  Function |
|---|---|---|
| [Navbar](https://v4-alpha.getbootstrap.com/examples/navbars/)  |  Component | Navigation header  |
|  [Jumbotron](https://v4-alpha.getbootstrap.com/examples/jumbotron/) | Component  |  Showcase key content |
|  [Typography](https://v4-alpha.getbootstrap.com/content/typography/) | CSS  | Different ways of displaying text  |
|[Grid System](https://v4-alpha.getbootstrap.com/layout/grid/) |  CSS |  Utilize 12-column system of Bootstrap to divide up your content |
|  [Responsive Helpers](https://v4-alpha.getbootstrap.com/utilities/responsive-helpers/) | Component  |  For documents, videos, etc. |
|  [ScrollSpy](https://v4-alpha.getbootstrap.com/components/scrollspy/) |  JavaScript | Enables functionality for the Navbar  |

## CSS
6.	Create a new VS Code file inside PersonalWebsite folder and name it main.css. 
7.	First, we need to add this line of code into your index.html document to reference our CSS file.
    ```html
    <head> 
    <title> Title goes here</title> 
    <link href="main.css" rel="stylesheet" type="text/css">
    </head>
    ```

7.	Add CSS code to main.css to assign style elements to tags or containers in your index.html file. Don’t forget to use a class selector (.containername) to apply style to classes. Example (.jumbotron) below:
    ```css
    body {     
        position: relative;
    } 

    .jumbotron {
        background-color: lightblue; 
    }

    h1 {    
        font-family: Georgia;
        text-align: center;     
        font-style: italic;
        padding-top: 50px; 
    } 
    
    p {     
        font-family: Arial;     
        font-size: 20px;     
    } 
    ```

**For help with CSS syntax rules, check out https://www.w3schools.com/css/css_syntax.asp 

## AZURE
8.	To host your website in the cloud, you will need to make two new accounts:
- GitHub -> Sign up at https://github.com 
- Azure -> If using an Azure Pass, please visit [http://microsoftazurepass.com](http://microsoftazurepass.com). Otherwise, sign up at https://microsoft.azure.com for a Free Trial.
  - Azure requires a Microsoft or work/school email account (@edu, @outlook, @hotmail, etc). If you don’t have one, create one at https://signup.live.com
9.	Once you have these accounts, and your website is ready for public viewing, upload your code to a new repository in GitHub.
10.	Sign up for the free trial in Azure, then create new Web App.
11.	Point this to your GitHub master branch and voila, you’re in the cloud!





