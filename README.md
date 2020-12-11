# aws-account-hardening

## Checklist
- Enable MFA for Root Account > DONE
- Change IAM Password Policy > DONE
```
Minimum password length is 128 characters
Require at least one uppercase letter from Latin alphabet (A-Z)
Require at least one lowercase letter from Latin alphabet (a-z)
Require at least one number
Require at least one non-alphanumeric character (! @ # $ % ^ & * ( ) _ + - = [ ] { } | ')
Password expires in 1 day(s)
Password expiration requires administrator reset
Allow users to change their own password
Remember last 24 password(s) and prevent reuse
```
- Deactivate Unsued STS Endpoints > DONE
- Enable CloudTrail in all Regions
- Setup AWS Single Sign-On
- (Optional) Customize Sign-in URL for IAM users in this account > DONE
```
https://jrdalino.signin.aws.amazon.com/console
```

## Tools
- IAM Policy Simulator: https://policysim.aws.amazon.com/home/index.jsp?#
- Web Identity Playground: https://web-identity-federation-playground.s3.amazonaws.com/index.html

## References
- https://aws.amazon.com/blogs/security/getting-started-follow-security-best-practices-as-you-configure-your-aws-resources/
