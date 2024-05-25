# MultiCall

A React + Redux library for fetching, batching, and caching chain state via the MultiCall contract.

## Setup

`yarn add smartswap-redux-multicall` or `npm install smartswap-redux-multicall`


```js
// Somewhere in your app
export const multicall = createMulticall({ reducerPath: 'multicall' })

// In your store's root reducer
export const rootReducer = combineReducers({
  // Other reducers
  [multicall.reducerPath]: multicall.reducer
})
```


