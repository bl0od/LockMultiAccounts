
# USAGE

1. make 'lock_multi_accounts' executable -> '$ chmod +x lock_multi_accounts'
2. run the script -> './lock_two_accounts'
4. script will lock today multi connections

## log files and directories
script will create these log files and directories:
* /var/log/lock_users/
* /var/log/lock_users/$TODAY
* /var/log/lock_users/$TODAY/connected_users_$TODAY.txt
* /var/log/lock_users/$TODAY/locked_users_$TODAY.txt
* /var/log/lock_users/$TODAY/log.txt
