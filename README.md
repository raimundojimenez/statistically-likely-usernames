# statistically-likely-usernames
This resource contains wordlists for creating statistically likely usernames for use in username-enumeration, simulated password-attacks and other security testing tasks.

When many users are present in an application or network, I normally approach password-attacks by guessing likely usernames, (rather than focusing on guessing too many passwords). This has several advantages (such as avoiding account lockout for example) and is almost always successful (usually several users have either "Password1", "password" or something equally trivial).

The core username lists here were generated orignally from US Census data, but I have recently updated this to use data indexed from Facebook. These lists have been tested extensively in live attacks against target networks and applications. This resulted in a very high degree of success (during authorised penetration tests). The initial reason for generating these was that I wanted to know when it was statistically worthwhile to try z.smith, compared to say j.jackson (or any other name) and create the most efficient set of guesses in the shortest possible time, based on popular formats.

![alt text](https://github.com/insidetrust/statistically-likely-usernames/blob/master/popular-names.JPG "Pereto curves are awesome")

A bunch of pre-canned lists are provided as follows:

top-formats-x45000.txt = Start here. This is an excellent list if you don't know the username format. 12 popular formats interleaved in statistically likely order.

john.smith-at-example.com-x50000.txt = A very common email address format (replace example.com with the target domain)

Formats of the following pre-canned lists should be self-evident:

jsmith-x50000.txt

smithj-x5000.txt # Should be longer?

johns-x5000.txt # Should be longer?

john-x10000.txt

smith-x5000.txt

jsmith2-x5000.txt

smithj2-1000.txt

john.smith-x50000.txt

jjsmith-x5000.txt  # Should be longer?

smithjj-x5000.txt # Currently missing?

johnjs-x5000.txt  # Should be longer?

johnsmith-x5000.txt  # Should be longer?

