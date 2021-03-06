# SOCIAL FISH

This is the official and only repository of the SocialFish project.

### MAINTAINERS

- **Alisson Moretto**, Twitter: [@A1S0N_][tw-alisson], Github: [@A1S0N][git-alisson]
- **Vandré Augusto**, Twitter: [@dr1nKoRdi3][tw-drink], Github: [@dr1nK0Rdi3][git-drink]

##### OTHER CONTRIBUTORS
- **greenmind-sec** [ Using Docker #46 ][pull-grenmind-sec]
- **tatsuryu** [Using context manager to control external processes #55][pull-tatsuryu] | [Added menu submodule #68][pull-tatsuryu2]

##### PREREQUISITES

- Python 3.x 
- pip3
- PHP
- curl
- git
- unzip

##### PYTHON 3 PREREQUISITES
- wget
- huepy

### CLONE

```sh
$ git clone https://github.com/UndeadSec/SocialFish.git
```

### RUNNING

```sh
$ cd SocialFish
$ sudo apt-get install python3-pip php unzip -y
$ sudo pip3 install -r requirements.txt
$ python3 SocialFish.py
```

### USING ANDROID/TERMUX

```sh
$ pkg install python php curl git unzip
$ git clone https://github.com/UndeadSec/SocialFish.git
$ cd SocialFish
$ pip install -r requirements.txt
$ python SocialFish.py
```

### USING DOCKER

Create image using docker
```sh
$ sudo docker build -t "socialfish" .
```

Using image
```sh
$ sudo docker run -it --rm "socialfish"
```

**VIDEO DEMO:** [https://youtu.be/FMYdnzjEBiQ][yt-demo]

### SCREENSHOT
![Shot](https://github.com/UndeadSec/SocialFish/blob/master/Images/sc.png)

## DISCLAIMER

TO BE USED FOR EDUCATIONAL PURPOSES ONLY

The use of the SocialFish is COMPLETE RESPONSIBILITY of the END-USER. Developers assume NO liability and are NOT responsible for any misuse or damage caused by this program.

"DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE."
Taken from [LICENSE](LICENSE).

[//]: # (links references)

[tw-alisson]: <https://twitter.com/A1S0N_>
[git-alisson]: <https://github.com/A1S0N>
[tw-drink]: <https://twitter.com/Dr1nkOrdi3>
[git-drink]: <https://github.com/dr1nk0rdi3>
[pull-grenmind-sec]: <https://github.com/UndeadSec/SocialFish/pull/46>
[pull-tatsuryu]: <https://github.com/UndeadSec/SocialFish/pull/55>
[pull-tatsuryu2]: <https://github.com/UndeadSec/SocialFish/pull/68>
[yt-demo]: <https://youtu.be/FMYdnzjEBiQ>

