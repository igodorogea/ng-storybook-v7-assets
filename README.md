# Reproduction of assets issue in storybook v7 with Angular

This is simplest example possible, containing:
1. a basic Angular app created with `ng new my-app`
2. storybook init on top of it `npx storybook@latest init` (latest was 7.5.0 ATMOW)

Angular app contains only an `<img />` tag loading an image from `assets`.

## Prerequisites

`npm install`

## Development server

To run Angular server - `npm start`

To run storybook - `npm run storybook`

## The problem

The image is not loaded in storybook server (404)