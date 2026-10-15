# Smart Split Bill & Tip Calculator

A single-page web app for splitting a meal or hangout bill: tip presets, tax/service charge, number of people, and a checklist of who has already paid.

Built for [MLH Global Hack Week: Hacktoberfest — Challenge 1: Build a Mini App with Cursor](https://www.mlh.com/events/global-hack-week-open-source-90/challenges/01a11d23-3841-86cf-2fa3-5e70600e8f08).

## Run it

Open `index.html` in a browser. No install or build step.

## Stack

HTML5, vanilla JavaScript, [Tailwind CSS via CDN](https://cdn.tailwindcss.com).

## Features

- Bill amount with live USD (`$`) or IDR (`Rp`) formatting
- Tip presets (0%, 10%, 15%, 20%) plus a custom percentage
- Optional tax / service charge
- People count with + / −
- Real-time totals: tip, tip per person, tax, grand total, amount each person pays
- Copy breakdown summary to clipboard for group chats
- Member checklist (saved in `localStorage`)
