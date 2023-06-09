### Hexlet tests and linter status:
![Last commit](https://img.shields.io/github/last-commit/rmanzman/frontend-project-11?color=32c854)
[![Build & Linter](https://img.shields.io/github/actions/workflow/status/rmanzman/rss-aggregator/rss.yml?color=32c854)](https://github.com/rmanzman/frontend-project-11/actions/workflows/rss.yml)
[![Maintainability](https://img.shields.io/codeclimate/maintainability/rmanzman/rss-aggregator?color=32c854&label=maintainability&logo=Code%20Climate&logoColor=32c854)](https://codeclimate.com/github/rmanzman/rss-aggregator/maintainability)

## RSS Aggregator

### Description:
RSS Aggregator - also termed a feed aggregator, feed reader, news reader, RSS reader, or simply an aggregator is a web application that aggregates syndicated web content such as online newspapers, blogs, podcasts, and video blogs (vlogs) in one location for easy viewing. The updates distributed may include journal tables of contents, podcasts, videos, and news items.

### Usage
- Just follow <a href="https://rss-aggregator-rmanzman.vercel.app/" target="_blank">this link</a>
- Insert the valid RSS-feed link to input
- Press 'Add' button

### For local usage and development
Make sure you have Node.js (14.0.x.x or higher) and npm installed.

1. Clone the project
```bash
git clone git@github.com:rmanzman/rss-aggregator.git
```
2. Install dependencies
```bash
cd rss-aggregator
make install
```
3. Use the following scripts according to your objectives
- To start a local server:
```bash
npm run start
```
- To build a project in development mode:
```bash
npm run build:dev
```
- To build a project in production mode:
```bash
npm run build:prod
```