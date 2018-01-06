# **README**

## Introduction

**What is Phlex?**  See <a href="https://github.com/d8ahazard/docker-phlex>Phlex - by d8atahazard</a>

**What is Phlex-able?**  This is a new project, using the original Phlex source.
I don't have a particular target in mind, I just know that Phlex was experiencing problems talking to my dockerized plex instance, and after fiddling around for quite a while I decided to make some changes to the code (Huzzah! it worked!)

After reviewing the code, I hope to initially simplify the existing codebase, then extend it to:
- Allow for more configuration options
- Use redis as a NoSQL cache for text-to-speech responses, images and session management
- Move all configuration (aside from listening ports!) to the application side
- Whatever else I feel like.

**Side note:** d8ahazard obviously doesn't love LAMP that much, seeing as he's using a LEMP stack...
