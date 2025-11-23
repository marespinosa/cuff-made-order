🛠 Tech Stack

Liquid

CSS3 / SCSS (or Tailwind, if used)
JavaScript / TypeScript (specify which one you used)
Update the above list to match your actual implementation.


✨ Install on CLI

1. Log in to Shopify via CLI
Run this in CMD, Git Bash, or Terminal:
shopify login --store cuff-collection-test.myshopify.com
This will open a browser window and ask you to confirm login.

2. Pull the Theme from Shopify
After logging in:
shopify theme pull --theme=173573538039
This downloads the theme files from Shopify into your local machine.


3. Run the Theme Locally (Development Mode)
Use this command:
shopify theme dev
This starts a local dev server and gives you a preview URL:
http://127.0.0.1:9292/products/cuff-ring
Your changes will hot-reload in the browser.

4. Push Changes Back to Shopify (Live Theme)
When you’re ready to publish updates:
shopify theme push --theme=173573538039

Note: 173573538039 is the original theme, make sure create branch first on git then connect on the theme on shopify. Do development on the staging theme.

✨ front end:
https://cuff-collection-test.myshopify.com/products/cuff-ring


✨ Files:

sections/
hero-product.liquid
customize-section.liquid (Customise section)
timeless-elegance.liquid:(Timeless Elegance)

snippets/
product-hero.liquid
product-info-variants.liquid

Product Template:
templates\product.cuff-new-tp.json:



✨ Developers POV:

✨ Design decisions 

90% pixel-perfect

✨ Challenges faced - Blockage

Product Featured - is not followed due to Ui/Ux designs. Its not good on desktop if the design is followed:
https://www.awesomescreenshot.com/image/57564352?key=a3683ae9e1b3bbb78de2c988574992b5 - this is the result instead


Finish and Polished followed the rules on css padding
https://www.awesomescreenshot.com/image/57564357?key=e50b09c25a58f1379cf5dd43f7a21c60 instead on the designs, since the 2 are different variant

Reasons:

To simplify development and avoid maintaining two separate codebases for desktop and mobile, I created the second version of the layout instead of strictly following the original design. 
This approach keeps the structure cleaner, reduces repetitive markup, and makes the styling easier to manage. 
By streamlining the layout, I can ensure the page remains responsive across all devices without relying on overly long or duplicated code.



👤 Author

Maricon Espinosa
Frontend Developer
(You can add your portfolio, LinkedIn, or website links)
