# React Native Dimensions API Returns Zero or Incorrect Dimensions

This repository demonstrates a bug in React Native where the `Dimensions` API may return incorrect or zero dimensions, especially during initial rendering. This can lead to layout problems and unexpected behavior.

## Problem Description

The `Dimensions.get('window')` method sometimes returns inaccurate screen width and height values, most often 0, before the layout is fully established.  This causes components to render improperly or crash. The problem is seemingly random and dependent on device and platform.