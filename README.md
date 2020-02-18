# ResponsiveHTML
Responsive HTML for boilerplate templates

# Basic Premise:
Mobile-Responsive Email Templates consist of only a few key formatting devices:
+ 1-Col Full Width
+ 2-Col Squish
+ 2-Col Bump Left over Right
+ 2-Col Bump Right over Left
+ 3-Col Squish
+ 3-Col Bump Left over Right
+ 3-Col Bump Right over Left

Assets within these "frames" can be set to inherit 100% of their parent widths, thus are able to respond to their changing dimensions.
Using the "@media screen" width in CSS allows of additional "Mobile, Tablet, Desktop, Ultra-Wide" resolutions and layouts.

# Usage:
The Responsive.HTML file contains a set of code-lite & basic "frame" modules that can be used to create most reasonable Email layouts.
In practice these frames would be stacked within a parent Table to control the overall email structure; designed to fit the end-customer's needs.
"Content Blocks" with width aware styles/classes would fill these frames as required.
An extensive library of Content Blocks (designed for either 1, 2, or 3 column placement) can be created to meet the end-customer's design requirements.

# Pros of the Template>Frame>Content method:
+ Highly modular design.
+ Small mobile-responsive HTML/CSS code base (less to edit when clients update renderers).
+ Simple and repeatable design rules for standardizing content creation.
+ Custom code allows for easy alteration by experienced emailers.

# Cons of the Template>Frame>Content method:
+ Less user friendly than "Clicks-not-Code" solutions.
+ Some of the HTML/CSS is highly specialized and not suitable for basic users.
+ Custom code doesn't update automatically like native content blocks do.
