# Sign the Clouder CLA

In order for your contribution to Clouder to be accepted, you have to sign the
Clouder Contributor License Agreement (CLA). More information about this
requirement is explained in the [FAQ](#faq).

## If you are an individual

1.  Read the [Individual Contributor License Agreement](icla-1.0.md)

2.  Modify your current pull request, or make a new pull request on
    [clouder-community/clouder](/clouder-community/clouder), adding a new file
    `<github-login>.md` under the [`doc/cla/individual`](individual/) directory.
    If your GitHub login is `yburon`, the file would be
    `doc/cla/individual/yburon.md`. The file should contain:

    ```
<country>, <date>

I hereby agree to the terms of the Clouder Individual Contributor License
Agreement v1.0.

I declare that I am authorized and able to make this agreement and sign this
declaration.

Signed,

<name> <email> https://github.com/<login>
```

    Replacing the following placeholders:

    * `<country>`: your country
    * `<date>`: current date in the form `YYYY-MM-DD`
    * `<name>`: your name
    * `<email>`: your email
    * `<login>`: your GitHub login

3. A Clouder R&D Team member will verify and accept your Pull Request. You can
make other pull requests, but we won't be able to merge them until your CLA
signature is merged.

## If you work for a company

1.  Read the [Corporate Contributor License Agreement](icla-1.0.md)

2.  Modify your current pull request, or make a new pull request on
    [clouder-community/clouder](/clouder-community/clouder), adding a new file
    `<lowercase-company-name>.md` under the [`doc/cla/corporate`](corporate/)
     directory. If the name of the company is Clouder, the file would be
    `doc/cla/corporate/clouder.md`. The file should contain:

    ```
<country>, <date>

<company-name> agrees to the terms of the Odoo Corporate Contributor License
Agreement v1.0.

I declare that I am authorized and able to make this agreement and sign this
declaration.

Signed,

<name> <email> https://github.com/<login>

List of contributors:

<name> <email> https://github.com/<login>
```

    The List of contributors should list the individual contributors working
    for the company.

    Replacing the following placeholders:

    * `<country>`: your country
    * `<date>`: current date in the form `YYYY-MM-DD`
    * `<name>`: your name
    * `<email>`: your email
    * `<login>`: your GitHub login

3. A Clouder R&D Team member will verify and accept your Pull Request. You can
make other pull requests, but we won't be able to merge them until your CLA
signature is merged.

# FAQ

## Why do i need to accept a CLA ?

The goal of having a Contributor License Agreement for Clouder is to:

* clearly define the terms under which intellectual property (patches, pull
  requests, etc.) have been contributed to the Clouder project

* protect the Clouder project and its users in case of legal dispute about the
  origin or ownership of any part of the code

* protect the Clouder project and its users from bad actors who would
  contribute and then try to withdraw their contributions or cause legal
  trouble, e.g. in the form of patent lawsuits

This is done by establishing a credible, non-repudiable record that each
contributor really intended to contribute to the Odoo project under specific
terms, and they had the right to make those contributions.

The CLA is for the protection of the contributors, the project and its users.
It does not change your rights to use your own contributions for any other
purpose.

The Clouder CLA is based on the Apache Software Foundation CLA v2.0, as
can be found on the Apache website.

This CLA is not a copyright assignment, it is a pure license agreement. You
keep the full copyright for your contributions, you simply provide an
irrevocable license to the project maintainer, Clouder S.A.S.U. to use, modify
and distribute your contributions without further restrictions.

## How does it work?

Each individual contributor (making contributions only on their own behalf) is
required to sign and submit the Individual Contributor License Agreement
(ICLA) of Clouder.  The agreement is executed by adding your name and
signature to the list of validated contributors inside the project source code.

If someone is unable to sign the CLA, their contributions will have to be
removed from the Odoo project.

In addition, if some or all of someone's contributions are written as part of
an employment by somebody else, the work may not belong to the contributor but
to their employer, depending on the contract terms and local laws. In that case
the employer needs to sign the Corporate Contributor License Agreement (CCLA),
including the names of all contributors allowed to make those contributions in
order for those contributions to be accepted.

The contributors should still sign the Individual CLA, in order to cover the
contributions that do not belong to the employer.

Contributors who have signed the ICLA without a CCLA from their employer should
be very careful.

The ICLA (section 4) is a legal declaration where the contributor states they
have the right to make the contributions. These contributors should only
submit contributions they are really entitled to license.


This CLA process is largely inspired by the CLA process of Odoo.