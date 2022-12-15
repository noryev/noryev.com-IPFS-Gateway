# noryev.com a conventional IPFS Gateway built on AWS

## I started [here](https://www.datastax.com/blog/how-to-make-run-public-ipfs-gateway-aws-fast-easy)

1. configure EC2 Instances(t2.large)
2. configure security group with custom TCP:8080, custom TCP: 4001-4002

figure out what its doing now, yesterday there was a few issues with the location of files I believe

use [this](https://discuss.ipfs.tech/t/ipfs-gateway-setup-configuration-problems-am-i-doing-this-right/15338) Its talking about another problem, not the same as this instance... Explore more

## lets try this walkthrough next: https://gist.github.com/NatoBoram/09d244ab02af16fecb62b917f7bee3c0

After setting this up ^^, I cannot put this on an open end-point until I get a bad-bits mechanism to keep banned content off of the gateway.

Go checkout joroppo's gateway and figure out if thats open or not...
