## Step 1 : Plugin Header Requirements & Activation Version check
register_activation_hook and version_compare

## Step 2 : Security checkup
if( !function_exists( 'add_action' ) )

## Step 3 : Create Custom Post type - movies

## Step 4 : Create meta boxes with add_meta_box

## Step 5 : Enqueue stylesheet to load in admin only for movie CPT
admin_enqueue_scripts, wp_enqueue_style and plugins_url

## Step 6 : Save metadata
save_post_ and update_post_meta

## Step 7 : Filter data with filter hook and placeholders
add_filter ( 'the_content' )

## Step 8 : Create table with dbDelta & Internationalizing all strings 

## Step 9 : Include rating option on front end
wp_enqueue_scripts, wp_enqueue_script

## Step 10 : Ajax request for rating from front end using wp_localize_script

## Step 11 : Handle AJAX Requests and Insert Data into the Database

## Step 12 : Averaging and Displaying the Rating

## Step 13 : Changing the Custom Post Types Table Columns title and data 

## Step 14 :  