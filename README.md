![Header](readme-img/header-img.png)

# Apotek Komunitas Sehat

This is a simple website for a pharmacy named Apotek Komunitas Sehat.

You may check the website <b>[here](https://apotek-ks.catkingdom.site/)</b>.

## About Project

This website consist of four sections. The first section displays some products that pharmacy has as well as the name and price. The second section contains a few health articles which embedded from instagram. The third section shows the locations of the pharmacies embedded from google maps and also the address of said pharmacies. The last section has "Contact Us" form for costomer consultation about medicines.

## Structure

- Navbar
- Header
- Main
    - Products
    - Health Contents
    - Locations
    - Contact Form
- Footer
    - Social Media
    - Copyright

## Languages

- HTML
- CSS

## Github Repository Set Up

1. Clone the repository from github
```
git clone https://github.com/RevoU-FSSE-4/milestone-1-mutiara-n.git
```

2. Create a new branch named "branch-1" to develop the website
```
git branch -b "branch-1"
```
3. After creating the new branch, use git checkout to navigate to the new branch
```
git checkout -b "branch-1"
```
4. Modify the website with personal information and push it once we're done
```
git add .
git commit -m "commit-message" // make sure to give details for the commit message
git push origin branch-1 
```
5. Once we're done, we can merge the branch into main branch.
```
git checkout main
git pull origin main
git merge develop // if there are any conflicts, we can resolve them manually
git commit -m "commit-message"
git push origin main
```

## Deployment Process

### Register and Deployment on Netlify

1. Register netlify account using github account.

    ![deploy](readme-img/deploy1.png)

    ![deploy](readme-img/deploy2.png)
    ![deploy](readme-img/deploy3.png)

2. Deploy the project using Netlify.
After we finished the register process, we could make a site based on the project we already have. Click "add new site" and choose "Import existing project".

    ![deploy](readme-img/deploy4.png)
    ![deploy](readme-img/deploy5.png)

3. Choose one of the github repositories that we wanted to deploy and fill the site name.
    
    ![deploy](readme-img/deploy6.png)
    ![deploy](readme-img/deploy7.png)
    ![deploy](readme-img/deploy8.png)

4. Wait for a few moments until the site finish the deployment and show the page below.

    ![deploy](readme-img/deploy9.png)

### Custom Domain Set Up

1. After we finish the site deployment, the next step is to set up a custom domain. First of all, we have to check the availability of our chosen custom domain name and choose the domain package we need.

    ![deploy](readme-img/deploy10.png)
    ![deploy](readme-img/deploy11.png)


2. Choose the package duration, then choose the payment method.

    ![deploy](readme-img/deploy12.png)
    ![deploy](readme-img/deploy13.png)

3. After we finished the payment, we would get the proof that the payment was a success!
    
    ![deploy](readme-img/deploy14.png)

4.  Register the domain by filling in your personal data.
After your domain registration is complete and you can begin to setup the custom domain.

    ![deploy](readme-img/deploy15.png)
    ![deploy](readme-img/deploy16.png)

5. Select the Domain Management menu on the Netlify site that has been deployed, then select Add Domain.

    ![deploy](readme-img/deploy17.png)

6. Add a custom subdomain according to the domain that has been registered.

    ![deploy](readme-img/deploy18.png)
    ![deploy](readme-img/deploy19.png)
    ![deploy](readme-img/deploy20.png)    


7. As we can see from the previous image, the site cannot run without DNS. DNS setup can be done on niagahoster by replacing <b>nameservers</b> on the domain overview page with Netlify nameservers.

    ![deploy](readme-img/deploy21.png)
    ![deploy](readme-img/deploy22.png)
    ![deploy](readme-img/deploy23.png)
    ![deploy](readme-img/deploy24.png)

8. Wait for approximately 24 hours until the Awaiting External DNS sign changes to Netlify DNS, then the process of adding the custom domain is complete.

    ![deploy](readme-img/deploy25.png)