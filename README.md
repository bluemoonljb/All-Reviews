# All-Reviews

Note: This project is a fork of All Reviews in Magento Connect. 

This project deals with following features:

    . Support 1.9.2.
    . Add pagination.
    . Be able to change number of reviews per page.

All Reviews allows you to display all reviews of your products on a single CMS page. Customers searching Google, Bing, Yahoo for "YOUR STORE Reviews" will be able to find a page controlled by you with recent reviews of your products.

You can see it in action here: http://www.kitchenhoods.ca/shop/reviews
Instructions

After you install the module, go to System > Configuration > EKO Internet Marketing > All Reviews. Click the General tab to expand it.

Now you need to configure the module. The default settings will work fine, but you can customize the way your reviews display by changing the different options

Once you're happy with the settings, go to CMS > Pages and create a new page. You can call it whatever you want, but we suggest using "Reviews" as the Page Title, and "reviews" as the URL Key.

On the content tab, paste the following code to display the reviews:

{{block type="allreviews/allreviews" name="all_reviews" template="allreviews/reviews.phtml"}}

After you've done that, visit yoursite.com/reviews and you should see reviews!

If you're having problems, please try the following:

    Clear your cache
    Log out of the admin and log back in if you get 404 Error for admin config page.
    IMPORTANT: You may need to recompile magento if you're using the compiler
    
