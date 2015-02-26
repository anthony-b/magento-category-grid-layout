# magento-category-grid-layout
I have created a custom grid layout for magento. All the files you need are in the Zip file that is attached.
You will need to copy "category_listing.phtml" into /app/design/frontend/default/YOUR_THEME_NAME/template/catalog/navigation (if the directory doesnt exist just create it).
Copy the text from "styles.css" into your themes style sheet. Be aware that the styling is very basic and will need to be modified to match your theme.
Now copy the text from the file "Put_into_block.txt" into a block and name the block. This block can be used in multiple times for different categories and will update depending on the category so there is only need to create 1 block for the whole site.
Then in the admin panel, go to the settings of the category where you are wanting to use the layout and in the Display Settings tab select Static Block from the Display Mode drop down, now select your new block from the CMS Block drop down.