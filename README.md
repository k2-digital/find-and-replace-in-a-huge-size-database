# OLD_DOMAIN - the old domain you want to replace it
# NEW_DOMAIN - the new domain you want to use
# -i.bak is used to create a backup for the file you want to modify
# YOUR_FILE - the file you want to modify

# Use Case
# Find and replace the old domain to new domain in a database dump from Magento
# Size is ~ 750MB, it is hard to open in any text editor in mac
# So execute sed to help replacing them in cli.

# Example
# sed -i.bak s/OLD_DOMAIN/NEW_DOMAIN/g YOUR_FILE
# sed -i.bak s/http:\\/\\/your_own_domain.com/http:\\/\\/your_new_domain.com/g your_file
