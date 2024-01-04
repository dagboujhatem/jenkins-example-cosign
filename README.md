# jenkins-example-cosign 

## To install the cosign in your Jenkins machine: 

You can refer to [this tutorail](https://edu.chainguard.dev/open-source/sigstore/cosign/how-to-install-cosign/#installing-cosign-with-the-cosign-binary) to install the cosign in your Jenkins machine.
You can use the `wget` command to install the most recent binary. In our example, the release we are installing is 2.0.0.

  `wget "https://github.com/sigstore/cosign/releases/download/v2.0.0/cosign-linux-amd64"`

After that type the following command in order to move the Cosign binary to your bin folder: 

  `sudo mv cosign-linux-amd64 /usr/local/bin/cosign`

Next, update permissions so that Cosign can execute within your filesystem.

  `sudo chmod +x /usr/local/bin/cosign`

Finally, verify all is done: 

  `cosign version`

You should have an outpout like that : 

![Cosign versoin output](https://alphasec.io/content/images/2022/11/Cosign-version-2.png)
