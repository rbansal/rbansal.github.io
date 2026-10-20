# rbansal.github.io

Hosts the public key for Home Assistant's Tesla Fleet integration at
`/.well-known/appspecific/com.tesla.3p.public-key.pem`, where Tesla's Fleet API
looks for it. This is the public half only; the private key stays on Home
Assistant. `.nojekyll` lets GitHub Pages serve the `.well-known` folder.
