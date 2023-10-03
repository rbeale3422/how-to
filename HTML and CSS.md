# GitHub Page Setup

1. Create a new public repository named: *username*.github.io, where *username* is your username on GitHub 

2. In **Quick Setup** section of new repository, click the ***creating a new file*** link

3. Enter **index.html** in the box where it says to ***name your file***

4. Copy and Paste the HTML code from below into **Edit new file** section

5. Click the **Commit new file** button to save your code and add the file to the repository.

6. Use your web browser of choice, and navigate to `https://username.github.io`

# HTML and CSS

- **HTML** stands for Hypertext Markup Language

- **CSS** stands for Cascading Style Sheets

## **HTML**

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Hello World</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <h1 class="reverse">Hello World</h1>
        <p>
            Here is a paragraph that contains a few sentences of content.
        </p>
    </body>
</html>
```

## Use Visual Studio Code to edit your new website

1. Ensure your **Account** is linked and syncing to GitHub

2. Close any open folders

3. Click on **Source Control** button

4. Choose **Clone Repository** button

5. Select **Clone from GitHub** from resulting options

6. Type or select `username/username.github.io` repository

7. Click on **Documents** in folder list and click the **Select Repository Location** button

8. Open the repository when given the option

9. Respond in the affirmative if asked about Trust in the resulting pop-up.

## Create the Stylesheet

1. Ensure that the `username.github.io` folder is open in Visual Studio Code

2. Hover mouse over the folder name and then click 'New File' icon

3. Enter **style.css** as new file name; hit **Enter** key to continue and open file as tab

4. Copy and Paste the CSS code from below into the new style.css tab

5. **Save** your file if you do not have autosave feature enabled (keyboard shortcut: `Ctrl + S`)

## **CSS**

```css
body {
    background-color: gray;
    color: black;
    font-family: Helvetica;
    font-size: 14px;
}

.reverse {
    background-color: black !important;
    color: white;
}
p {
    padding: 20px;
}
```

## Upload Changes from Visual Studio Code to your new website

1. Click on **Source Control** button

2. Click the **+** button to **Stage All Changes**

3. Enter a message to accompany your upload (for audit purposes)

4. Click the **check mark** button to **Commit**

## View Your Website

- Navigate to `https://username.github.io`
