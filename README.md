# React Native FlatList Empty List Bug

This repository demonstrates a common bug in React Native where a FlatList component renders an empty list even after successfully fetching data.  The issue stems from how asynchronous operations and state updates interact within the component's lifecycle. This example uses `useEffect` and `fetch` to simulate an API call and highlights potential pitfalls.

## Bug Description

The `DataList` component fetches data from a JSONPlaceholder API. Despite successfully fetching data, the FlatList remains empty.  The error handling is present, but the core problem lies in the data handling or timing of state updates.