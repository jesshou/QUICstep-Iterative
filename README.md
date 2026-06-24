/\* Protocol: QUICstep

- Title: QUICstep: Evaluating connection migration based QUIC censorship circumvention
- Authors: Seungju Lee, Mona Wang, Watson Jia, Qiang Wu, Henry Birge-Lee, Liang Wang, Prateek Mittal
- Link: https://petsymposium.org/popets/2026/popets-2026-0014.pdf
- Description: This workflow is the QUICstep protocol written in SAPIC+. Version history shows line by line addition.

\*/

Notes:
Iteration 1 06/24/2026:

- Set up boilerplate template and set up initial secret logic for client.

Interation 2 06/24/2026:

- Wrote headings and comments before each major event:
  - C/S deriving Initial Secret keys
  - C Sending ClientHello
  - S Receiving ClientHello
  - S Send ServerHello and derive TLS shared secret
  - C Receiving ServerHello and deriving TLS shared secret
- Wrote lemmas:
  - C sends ClientHello
  - S receives ClientHello
  - S and C derive the same TLS shared secret
- All lemmas successful
