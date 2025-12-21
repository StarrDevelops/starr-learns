Topic: Commit Metadata

The Identity String
Author Definition: Git defines an author as a combination of user.name and user.email.

Consistency: Any change to the global email variable results in a new "identity" in the repository history, even if both emails point to the same GitHub user.

Transport vs. Identity: SSH keys handle authentication (permission to push), while Git config handles attribution (who gets the credit).