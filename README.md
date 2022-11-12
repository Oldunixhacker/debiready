# Debiready

Debiready is a Debian desktop installer powered by `debootstrap`.

## Images

The Debiready project is creating Debian live and install images with Debiready in place
of Calamares/Debian-Installer, using the same technolegies. Go to the releases page for
downloads.

## Testing

Debiready should not be tested on live images but it can be tested on a hard disk
Debian installation:

```
git clone https://github.com/TylerMS887/debiready
cd debiready
. build.sh
cd build
chmod +x debiready
debiready --test
```
