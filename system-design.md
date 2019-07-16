# System Design Consideration

1. Make wrapper(facade) for logging lib, so you can switch logging implementation without breaking your code 
   * It will also nice when you provide loggingg for sql
2. If you think that a feature will be user configurable, use config file instead of convention
3. 
