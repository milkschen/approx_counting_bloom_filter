# Approx Counting Bloom Filter

This is a prototype for the approximate counting Bloom filter (ACBF).

Typical Bloom filters only anwer the membership queries, but doesn't supoprt counts and deletions.
A counting Bloom filter supports counts and deletions, but with a large memory overhead. 
We apply a probablistic approach on counting Bloom filters to support probablistic count queries and deletions.
We provide notebooks to compare the ACBF theory and its emprical results.

