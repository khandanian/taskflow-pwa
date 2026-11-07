# TaskFlow PWA

A Persian-first, right-to-left, installable project and task management demo.

## Live demo

https://khandanian.github.io/taskflow-pwa/

## Features

- Multiple projects and tasks, with priority, status, deadline, and notes
- Kanban board with drag-and-drop on desktop and move buttons for touch devices
- Search and project/priority filters
- Progress statistics
- Browser-local persistence using localStorage
- Offline support via service worker and installable web app manifest
- Responsive design, no server or build tooling required

## Deployment

Open **Settings → Pages → Build and deployment → Source → GitHub Actions**. A deployment workflow is included in `.github/workflows/deploy.yml`.

## Local development

Serve this directory using `python -m http.server 8080`, then open http://localhost:8080. Service workers do not work when opening the HTML file directly with `file://`.

This is a portfolio demonstration. It stores data in the current browser only and does not sync across devices.
