dans usersApiSlice:
   - 'keepUnusedDataFor':
    Defaults to 60 (this value is in seconds). This is how long RTK Query will keep your data cached for after the last component unsubscribes. For example, if you query an endpoint, then unmount the component, then mount another component that makes the same request within the given time frame, the most recent value will be served from the cache.