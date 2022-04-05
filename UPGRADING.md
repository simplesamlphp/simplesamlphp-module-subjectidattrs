# Upgrade notes

## 1.x to 2.0

### Hash generation BC breaking change

The algorithm to calculate the hash for the pairwise-id has changed,
because it contained a security weakness. This means new hashes
will be generated for each user.
