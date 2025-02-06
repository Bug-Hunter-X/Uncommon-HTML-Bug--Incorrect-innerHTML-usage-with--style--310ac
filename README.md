# Uncommon HTML Bug: Incorrect innerHTML usage with <style>

This repository demonstrates an uncommon bug related to the use of `innerHTML` in HTML.  The bug arises from attempting to modify the content of a `<style>` tag dynamically using `innerHTML`. This approach is generally not recommended and can lead to unexpected behavior.

## Bug Description
The provided HTML code attempts to hide a div element (#myDiv) by dynamically injecting a CSS rule via `innerHTML`. This does not work as expected.

## Solution
The solution uses appropriate CSS manipulation techniques to correctly hide the div.