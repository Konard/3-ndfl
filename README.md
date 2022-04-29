# 3-ndfl
3-NDFL document generation for dividend tax payment.

`3-ndfl.pdf` can be converted to `3-ndfl.dc1` file using https://t.me/invest_3ndfl_bot from https://investor-declaration-3-ndfl.ru/

Then `3-ndfl.dc1` can be converted to `3-ndfl.xml` using `https://www.nalog.gov.ru/rn52/program/5961249/` program.

Convertation from `3-ndfl.dc1` to `3-ndfl.xml` can be automated as JS script to be crossplatform and independent from Windows.

Note that `3-ndfl.xml` should use specific cyrillic compatible encoding. (At the moment it is unknown which one exactly). It should be Unicode for storage in GitHub, may be it is also possible to upload to `nalog.ru` using Unicode.
