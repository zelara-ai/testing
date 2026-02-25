# Testing Module Wiki

## Purpose

Diagnostic and testing features for Zelara development and device communication validation.

## Features

### Image Inversion Test
- Tests full round-trip image processing pipeline
- Mobile captures/sends image → Desktop processes → Mobile receives result
- Validates WebSocket communication and base64 encoding

### Connection Diagnostics
- WebSocket connection status
- Latency measurements
- Token validation testing

## Architecture

- Mobile: React Native components
- Desktop: Tauri + React components
- Communication: WebSocket via DeviceLinkingService
