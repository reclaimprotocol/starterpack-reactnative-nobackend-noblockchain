# Reclaim Starter Pack - React Native Frontend, no backend, no blockchain

You can use this starter pack if you need your users to prove some credential. This starter pack will let you create and verify proofs on the frontend itself - you can write business logic like taking some action once the proof has been generated and verified. An `onSuccess` callback is exposed that you can modify.

## Things you need to change
- in App.js, you need to change the `requestedProofs` object. You can learn more about how to populate this object [here](https://docs.reclaimprotocol.org/providers/http-provider), or can use one of the prebuilt ones from [here](https://dev.reclaimprotocol.org)
- You need to also modify the code inside the `onSuccess` and `onError` callbacks in App.js
