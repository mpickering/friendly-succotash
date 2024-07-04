Resolving dependencies...
Build profile: -w ghc-9.6.2 -O1
In order, the following will be built (use -v for more details):
 - boot-issue-0.1.0.0 (lib) (first run)
Configuring library for boot-issue-0.1.0.0..
Preprocessing library for boot-issue-0.1.0.0..
Building library for boot-issue-0.1.0.0..
Unexpected non-cycle [boot-issue-0.1.0.0-inplace:D [boot-issue-0.1.0.0-inplace:D {-# SOURCE #-},
                                                    boot-issue-0.1.0.0-inplace:B],
                      boot-issue-0.1.0.0-inplace:B [boot-issue-0.1.0.0-inplace:C],
                      boot-issue-0.1.0.0-inplace:C [boot-issue-0.1.0.0-inplace:A,
                                                    boot-issue-0.1.0.0-inplace:D],
                      boot-issue-0.1.0.0-inplace:A [boot-issue-0.1.0.0-inplace:D {-# SOURCE #-}]]
Error: cabal: Failed to build boot-issue-0.1.0.0.
