# Habit-Builder-And-Daily-Organizer
Personal productivity dashboard — An Advanced Trello board with AI task categorisation, habit tracking, and life goal breakdown. Built with vanilla HTML/CSS/JS and the Claude API.
# Daily Habit Tracker & To-Do List

A personal productivity dashboard built to replace a fragmented workflow across Trello, a habit tracker, and Google Calendar.

## What it does

- 21-day rolling Kanban board starting from today
- AI-powered task categorisation using the Claude API — type a task and it guesses the category, or use @R, @FF, @H etc. to set it instantly
- Daily habit tracking with tap-to-fill water and contact counters
- Fireworks animation on task completion
- Today's wins archive showing everything completed with timestamps
- Weekly goal tracking for relationship activities, creative activities, and physical activity
- Life balance breakdown chart across 5 categories: Health, Financial Freedom, Relationships, Mental Health, and Hobbies

## Tech stack

Vanilla HTML, CSS, and JavaScript — no frameworks, no build tools. One file.
Claude API (Anthropic) for AI task categorisation and weekly roundup generation.
Google Apps Script for the live version, which reads Google Calendar directly on page load.
Chart.js for the breakdown pie chart.
GitHub Pages for hosting this demo.

## Live demo

[View the demo](https://yourusername.github.io/my-space)

## How it works

The demo version uses anonymised placeholder data. The live version connects to Google Calendar via Google Apps Script and categorises events automatically. All task data saves to localStorage, so nothing is lost between sessions.
