# Lab 1 submission

### Output of `curl` against `/health`, `/notes`, and `POST /notes`

![[Pasted image 20260609172958.png]]
![[Pasted image 20260609173020.png]]
![[Pasted image 20260609191240.png]]

### Output of `git log --show-signature -1` showing **Good** signature

Nedeed to run command below for task to be done: 
`echo "elfsgithub@gmail.com $(cat ~/.ssh/id_ed25519.pub)" > ~/.ssh/allowed_signers`

![[Pasted image 20260609192828.png]]

### A screenshot of the Verified badge on your platform's PR/commit page

![[Pasted image 20260609193127.png]]

### A 2-3 sentence explanation: _why_ signed commits matter (referencing the xz-utils March 2024 story from Lecture 1)

Story from lecture - in **March 2024**, an attacker (account `JiaT75`) maintained the **xz-utils** project for two years and slipped in a backdoor that nearly compromised every SSH daemon on Linux. Because there was no sighning for commits it could be anyone who could commit compromised changes and there is no way of proving otherwise. Signed commits are proven to be from at least developer's device that holds this key, so that adds at least one security layer, which is good

Nocised that folder was copied into system folder, changed lokation of it.

### Task 2

