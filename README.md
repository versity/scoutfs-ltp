# scoutfs-ltp
LTP tests for Scoutfs

More info about LTP test suite: https://github.com/linux-test-project/ltp

To install
git clone git@github.com:versity/scoutfs-ltp.git

These tests are already compiled for CentOS 7.x


To run the test suite
cd scoutfs ; ./runltp -p -q -l /var/tmp/ltp -d /mnt/scoutfs -f fs
