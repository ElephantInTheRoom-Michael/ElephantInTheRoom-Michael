# Cookbook

Hugo site to contain my recipes.

Features:
- Search recipes by category, tag, or ingredients
- Show a special cooking view with large text and one step at a time
- Retrieve information about nutrition and cost
- Allow variations of a recipe
- Print recipes

## Related

### HugoTheme-Cookbook

Hugo theme for displaying recipes

### Food

Ruby on Rails API to store and retrieve ingredient cost and nutrition

Features:
- Submit recipe ingredients to get total cost and nutrition
- Track cost over time with different tracking for normal cost and sales
- List ingredients that have not been updated recently to focus on at grocery store
- Scan uploaded receipt for prices
- Scan uploaded nutrition label
- Retrieve nutrition for basic ingredients from a good source of information
- Look up ingredient by barcode

Provide SDKs for Ruby, Typescript, and Kotlin

### Cookbook App

Retrieve metadata from live cookbook website for recipes and display in app format
with similar features to website like cooking view.

Manage food cost and nutrition data.

# Simple Workflow Clients

Create AWS SWF clients in Ruby, Kotlin, and Scala (Akka).

# EV Driving

Android App that connects to an OBD device while driving.

Features:
- Calculate expected consumption for a route, getting data from a map source and weather data
- For every unit of travel check expected vs actual consumption
- Show graph showing expected battery percent at each mile in drive, with upper and lower bounds

# Godot Addons Manager

Run a script to install Godot addons from GitHub

Needs a config file with the GitHub URL to get the zip file, and optionally a commit or tagged version.
Will update config file upon install with installed path and current commit ID.

Download zip to a temp directory, and move content from the unzipped projects addons directory to the 
editing projects addons directory.
