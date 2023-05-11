---
x-trestle-set-params:
  ia-5.18_prm_1:
    values:
  ia-5.18_prm_2:
    values:
x-trestle-global:
  sort-id: ia-05.18
---

# ia-5.18 - \[Identification and Authentication\] Password Managers

## Control Statement

- \[(a)\] Employ {{ insert: param, ia-5.18_prm_1 }} to generate and manage passwords; and

- \[(b)\] Protect the passwords using {{ insert: param, ia-5.18_prm_2 }}.

## Control guidance

For systems where static passwords are employed, it is often a challenge to ensure that the passwords are suitably complex and that the same passwords are not employed on multiple systems. A password manager is a solution to this problem as it automatically generates and stores strong and different passwords for various accounts. A potential risk of using password managers is that adversaries can target the collection of passwords generated by the password manager. Therefore, the collection of passwords requires protection including encrypting the passwords (see [IA-5(1)(d)](#ia-5.1_smt.d)) and storing the collection offline in a token.