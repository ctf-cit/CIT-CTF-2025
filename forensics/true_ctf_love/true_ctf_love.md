# True CTF Love

I got this strange email from another CTF participant not too long ago. I am just not sure what they mean by this...

Do you love CTFs as much as they do?

**SHA256:** `07cb654ce87444f158a52228848eb4eb501738913dfca44a2f227fb73ee9ed4b`

### Solution

Upon opening the challenge `.eml` file, the flag is hidden in the DKIM-Signature portion of the email header, Base64 encoded to match the actual DKIM-Signature of the email.

```
b=V293LCB3aGF0IGEgYmVhdXRpZnVsIGxpdHRsZSBwb2VtLiBJIGFsbW9zdCBzaGVkI
	 GEgdGVhciByZWFkaW5nIHRoYXQuIEhvcGVmdWxseSB5b3UgbGVhcm5lZCBtb3JlIGFi
	 b3V0IGVtYWlsIGhlYWRlcnMuIEJ1dCBzZXJpb3VzbHksIGl0IGdldHMgbWUgd29uZGV
	 yaW5nLi4uIGRvIHlvdSBsb3ZlIENURnMgYXMgbXVjaCBhcyB0aGV5IGRvPwoKQ0lUe2
	 lfbDB2M19jdGYkX3QwMH0=
```

Once it is Base64 decoded, you get this:

```
Wow, what a beautiful little poem. I almost shed a tear reading that. Hopefully you learned more about email headers. But seriously, it gets me wondering... do you love CTFs as much as they do?

CIT{i_l0v3_ctf$_t00}
```

## Flag

> `CIT{i_l0v3_ctf$_t00}`