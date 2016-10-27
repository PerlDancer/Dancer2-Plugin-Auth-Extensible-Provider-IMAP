# NAME

Dancer2::Plugin::Auth::Extensible::Provider::IMAP - IMAP authentication provider for Dancer2::Plugin::Auth::Extensible

# DESCRIPTION

This class is a generic IMAP authentication provider.

See [Dancer2::Plugin::Auth::Extensible](https://metacpan.org/pod/Dancer2::Plugin::Auth::Extensible) for details on how to use the
authentication framework.

In order to use SSL connections to the server you must install
[IO::Socket::SSL](https://metacpan.org/pod/IO::Socket::SSL).

# ATTRIBUTES

## host

IMAP server name or IP address. Required.

## options

A hash reference of options to be passed to ["new" in Net::IMAP::Simple](https://metacpan.org/pod/Net::IMAP::Simple#new).

# METHODS

## authenticate\_user $username, $password

## get\_user\_details $username

Not appropriate for this provider so returns nothing.

## get\_user\_roles $username

Not appropriate for this provider so returns nothing.

# SEE ALSO

[Dancer2](https://metacpan.org/pod/Dancer2), [Dancer2::Plugin::Auth::Extensible](https://metacpan.org/pod/Dancer2::Plugin::Auth::Extensible), [Net::IMAP::Simple](https://metacpan.org/pod/Net::IMAP::Simple).

# AUTHOR

Peter Mottram (SysPete), `<peter at sysnix.com>`

# BUGS

Please report any bugs or feature requests via the project's GitHub
issue tracker:

[https://github.com/SysPete/Dancer2-Plugin--Auth-Extensible-Provider-IMAP/issues](https://github.com/SysPete/Dancer2-Plugin--Auth-Extensible-Provider-IMAP/issues)

I will be notified, and then you'll automatically be notified of
progress on your bug as I make changes. PRs are always welcome.

# SUPPORT

You can find documentation for this module with the perldoc command.

    perldoc Dancer2::Plugin::Auth::Extensible::Provider::IMAP

You can also look for information at:

- [GitHub repository](https://github.com/PerlDancer/Dancer2-Plugin-Auth-Extensible-Provider-IMAP)
- [meta::cpan](https://metacpan.org/pod/Dancer2::Plugin::Auth::Extensible::Provider::IMAP)

# LICENSE AND COPYRIGHT

Copyright 2016 Peter Mottram (SysPete).

This program is free software; you can redistribute it and/or modify it
under the terms of the the Artistic License (2.0). You may obtain a
copy of the full license at:

[http://www.perlfoundation.org/artistic\_license\_2\_0](http://www.perlfoundation.org/artistic_license_2_0)

Any use, modification, and distribution of the Standard or Modified
Versions is governed by this Artistic License. By using, modifying or
distributing the Package, you accept this license. Do not use, modify,
or distribute the Package, if you do not accept this license.

If your Modified Version has been derived from a Modified Version made
by someone other than you, you are nevertheless required to ensure that
your Modified Version complies with the requirements of this license.

This license does not grant you the right to use any trademark, service
mark, tradename, or logo of the Copyright Holder.

This license includes the non-exclusive, worldwide, free-of-charge
patent license to make, have made, use, offer to sell, sell, import and
otherwise transfer the Package with respect to any patent claims
licensable by the Copyright Holder that are necessarily infringed by the
Package. If you institute patent litigation (including a cross-claim or
counterclaim) against any party alleging that the Package constitutes
direct or contributory patent infringement, then this Artistic License
to you shall terminate on the date that such litigation is filed.

Disclaimer of Warranty: THE PACKAGE IS PROVIDED BY THE COPYRIGHT HOLDER
AND CONTRIBUTORS "AS IS' AND WITHOUT ANY EXPRESS OR IMPLIED WARRANTIES.
THE IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR
PURPOSE, OR NON-INFRINGEMENT ARE DISCLAIMED TO THE EXTENT PERMITTED BY
YOUR LOCAL LAW. UNLESS REQUIRED BY LAW, NO COPYRIGHT HOLDER OR
CONTRIBUTOR WILL BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, OR
CONSEQUENTIAL DAMAGES ARISING IN ANY WAY OUT OF THE USE OF THE PACKAGE,
EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
