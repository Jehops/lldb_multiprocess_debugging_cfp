# Call for proposals: Multiprocess support for LLDB

The FreeBSD Foundation is soliciting proposals to implement LLDB multiprocess
debugging on FreeBSD.

## Background

LLDB, the debugger associated with the LLVM compiler infrastructure, is part of
the FreeBSD base system.  Over the past few years, contracted work has been
completed to expand LLDB's functionality on FreeBSD to match that of GDB, the
GNU debugger.  The work has included:

      - development of a remote process plugin using a modern client-server layout
      - implementation of follow-fork, follow-vfork, follow-spawn, and SaveCore
      - several improvements to FreeBSD kernel debugging
      - improvements to multiprocess debugging

## Remaining Work

Work remains to implement full LLDB multiprocess debugging on FreeBSD.  Some of
the tasks include

1. completing threaded communication support
2. extending threaded communication support to asynchronous notification packets
3. implementing multiprocess support
4. improving and implementing tests and documentation

## Proposal Guidelines

- https://freebsdfoundation.org/get-involved/project-proposal-overview/
- https://freebsdfoundation.org/wp-content/uploads/2017/06/FreeBSDProposalSubmission.pdf
- http://issue.freebsdfoundation.org/publication/?m=33057&i=263272&view=articleBrowser&article_id=2037083&ver=html5

The Foundation will accept proposals at proposal@freebsdfoundation.org until a
successful candidate is found.
