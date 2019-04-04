# JS Based Twitter Fetcher for Drupal / GovCMS

## Purpose
A Twitter feed for GovCMS that is compatible with IE 10/11 unlike the current version of the standard Twitter iFrame embed.
Also allows the feed to be styled freely.

## Based on
Twitter Post Fetcher v18.0.3.
Coded by Jason Mayes 2015.
www.jasonmayes.com

## Intructions
- Copy files inside CSS and JS folders into matching folders inside your theme.
- Add the contents of twitter-fetcher.libraries and twitter-fetcher.theme into the matching files in you theme
- And the contents of block HTML to a block you want to display your twitter feed.

css/twitter-fetcher.css - Use to style the feed however you want

js/twitter-fetcher.js - Options for the feed can be set an the bottom of the file in the configProfile object, make sure to set 'screenName' to the desired Twitter screenName. Or alter to modify markup produced.

test.html - Use for local testing. Not needed for Drupal deployment.
