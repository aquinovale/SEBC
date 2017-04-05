[libdefaults]
default_realm = HADOOP.LOCAL
dns_lookup_kdc = true
dns_lookup_realm = false
ticket_lifetime = 86400
renew_lifetime = 604800
forwardable = true
default_tgs_enctypes = aes256-cts-hmac-sha1-96
default_tkt_enctypes = aes256-cts-hmac-sha1-96
permitted_enctypes = aes256-cts-hmac-sha1-96
udp_preference_limit = 1
kdc_timeout = 3000
[realms]
HADOOP.LOCAL = {
kdc = ip-10-159-126-189.ec2.internal
admin_server = ip-10-159-126-189.ec2.internal
}
