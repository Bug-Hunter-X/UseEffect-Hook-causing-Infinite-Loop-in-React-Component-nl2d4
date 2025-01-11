# React useEffect Infinite Loop Bug

This repository demonstrates a common React bug involving the `useEffect` hook.  The `useEffect` hook, when improperly used, can lead to an infinite loop, significantly impacting performance and potentially crashing the application.

The bug occurs because the effect runs after every render, triggering a continuous update cycle.