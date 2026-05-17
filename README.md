# NexWave

NexWave is a decentralized offline communication platform designed for Android devices during disaster and emergency situations where traditional communication infrastructure becomes unavailable.

Using Bluetooth Low Energy (BLE) mesh networking, devices can automatically discover nearby users, establish direct peer-to-peer connections, and relay messages across multiple devices without requiring internet, WiFi, or mobile networks.

The goal of NexWave is to provide reliable emergency communication during:
- natural disasters
- internet shutdowns
- remote area emergencies
- network failures

---

## Platform

- Android Application
- Built using React Native and Expo

---

## Features

- Offline peer-to-peer communication
- Bluetooth Low Energy (BLE) mesh networking
- Automatic nearby device discovery
- Multi-hop message forwarding
- Emergency SOS broadcasting
- Local message storage
- Real-time device scanning
- Cross-device communication without internet

---

## Tech Stack

### Frontend
- React Native
- Expo
- TypeScript

### Networking
- react-native-ble-plx
- Bluetooth Low Energy (BLE)

### Storage
- AsyncStorage

---

## Project Structure

```bash
src/
 ├── app/
 │    ├── index.tsx
 │    ├── mesh.tsx
 │    ├── messaging.tsx
 │    └── sos.tsx
 │
 ├── bluetooth/
 ├── mesh/
 ├── messaging/
 ├── storage/
 ├── utils/
 └── assets/
