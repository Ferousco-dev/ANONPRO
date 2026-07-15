# AnonPro 🕶️

> An anonymous social media platform with professional features — post, share, and connect without revealing your identity.

<p align="left">
  <img src="https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white" alt="Dart">
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white" alt="Supabase">
</p>

## Overview

AnonPro is a cross-platform Flutter application that lets users interact on a social feed anonymously while keeping a polished, professional experience. It uses Supabase for authentication, data, and storage.

## Features

- 🔒 Anonymous posting and interactions
- 🖼️ Image upload, cropping, and cached network images
- ♾️ Staggered/masonry feed layouts with shimmer loading states
- 🕒 Human-friendly timestamps (`timeago`)
- 🔄 State management with Provider
- ☁️ Backend powered by Supabase (auth, database, storage)

## Tech Stack

- **Framework:** Flutter (Dart, SDK ≥ 3.0.0)
- **Backend:** Supabase (`supabase_flutter`)
- **State:** Provider
- **Media:** `image_picker`, `image_cropper`, `extended_image`, `cached_network_image`
- **Networking:** `dio`, `http`
- **Targets:** Android · Web · Linux · Windows

## Getting Started

```bash
git clone https://github.com/Ferousco-dev/ANONPRO.git
cd ANONPRO
flutter pub get
```

Add your Supabase credentials (URL + anon key) to your environment/config, then run:

```bash
flutter run
```

## Project Structure

```
lib/          # application source
supabase/     # database schema & migrations
assets/       # images and static assets
android/ web/ linux/ windows/   # platform targets
```
