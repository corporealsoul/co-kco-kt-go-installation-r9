### GO,

**Go Download,** https://go.dev/doc/install

`[anup@rhel-92-04 ~]$ wget https://go.dev/dl/go1.20.5.linux-amd64.tar.gz`

<br>

### Go installation,

**Remove any previous Go installation,**

`[anup@rhel-92-04 ~]$ sudo mkdir /home/anup/go`

`[anup@rhel-92-04 ~]$ rm -rf /home/anup/go && tar -C /home/anup -xzf go1.20.5.linux-amd64.tar.gz`

<br>

**Add /usr/local/go/bin to the PATH environment variable,**

`[anup@rhel-92-04 ~]$ export PATH=$PATH:/home/anup/go/bin`

`[anup@rhel-92-04 ~]$ echo $PATH`

<br>

**Verify installation,**

`[anup@rhel-92-04 ~]$ go version`

<br>
