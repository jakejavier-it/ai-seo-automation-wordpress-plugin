# AI Brand-Aware SEO Automation Plugin

The AI Brand-Aware SEO Automation Plugin is an installable WordPress plugin developed to simplify and speed up SEO content workflows.

It allows users to provide target keywords, select a supported GPT model, and connect the required API keys. The plugin then generates SEO-focused blog content, including the meta title, meta description, article content, tags, and related images.

Users can also schedule a preferred publishing date. Once configured, the plugin automatically creates and publishes the blog post and sends an email notification when the content has been scheduled or published.

## Technologies and Services Used

- WordPress
- PHP
- OpenAI API
- Gemini API
- WordPress Cron
- Email notifications
- HTML and CSS
- WordPress database and post-management functions

## Main Features

- Installable on WordPress websites
- Accepts target keywords for content generation
- Supports configurable GPT models through API keys
- Generates SEO-focused meta titles and meta descriptions
- Generates complete blog-post content
- Creates relevant tags
- Generates blog images using the Gemini API
- Allows users to select a preferred publishing date
- Automatically schedules and publishes generated blog posts
- Sends email notifications when content is scheduled or published
- Provides an interface for managing the content-generation process

## How It Works

1. The user installs and activates the plugin on a WordPress website.
2. The user enters or uploads the target keywords.
3. The user selects the supported GPT model and provides the required API key.
4. A Gemini API key can be added for image generation.
5. The user selects the preferred publishing date.
6. The plugin generates the blog title, metadata, content, tags, and image.
7. WordPress Cron schedules the blog post for automatic publishing.
8. The plugin sends an email notification when the post is scheduled or published.

## My Contributions

- Designed the plugin pages, tabs, and basic user interface
- Contributed to the AI-assisted blog-generation workflow
- Helped implement scheduled publishing through WordPress Cron
- Contributed to email-notification functionality
- Integrated content-generation features for metadata, blog content, tags, and calls to action
- Participated in testing and debugging the plugin
- Identified software issues and documented fixes and improvements
- Helped prepare the plugin for its beta release

## Current Limitations

The plugin currently uses the default WordPress blog-post structure for generated content.

Automatic layout customization is not yet supported. Websites that use custom themes, templates, or page builders may not display the generated post exactly as intended. In these cases, the post layout and formatting may need to be adjusted manually after generation.

The plugin focuses mainly on automating content creation, SEO metadata, images, scheduling, and publishing rather than automatically designing custom page layouts.

## Security Notice

API keys, passwords, authentication credentials, and private website information are not included in this public repository.

Users should securely store their own OpenAI and Gemini API keys and should never publish them inside source code or screenshots.

## Project Status

The plugin was developed as an internship project and reached a beta stage.

A public live demonstration and downloadable plugin file are not currently provided in this repository. This repository serves as portfolio documentation and presents selected information about the plugin, its features, and my contributions.

## Internship Project Notice

This plugin was developed as part of an internship project. This repository documents the project for portfolio purposes and does not include confidential company information, private credentials, or restricted source code.
