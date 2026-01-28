# damnvulnerabledefi-ariel

Damn Vulnerable DeFi est un playground de sécurité smart‑contracts.  
Ce dépôt contient **mes solutions** pour la version **v4.1.0**, avec tous les tests Foundry validés.

---

## Installation

1. Cloner le dépôt
2. Copier `.env.sample` vers `.env`
3. Ajouter un RPC valide dans `.env` (nécessaire pour PuppetV3 et CurvyPuppet)


---

## Lancer les tests

Test global : forge test -vv


Test ciblé (exemple) : forge test test/withdrawal/Withdrawal.t.sol --match-test test_withdrawal

---

## Résumé des tests (rendu)

Commande utilisée :


Résultat :

- **36 tests passés, 0 échec**
- Suites validées :
  - abi-smuggling
  - backdoor
  - climber
  - compromised
  - curvy-puppet
  - free-rider
  - naive-receiver
  - puppet
  - puppet-v2
  - puppet-v3
  - selfie
  - shards
  - side-entrance
  - the-rewarder
  - truster
  - unstoppable
  - wallet-mining
  - withdrawal

---

## Notes

- Les challenges avec fork mainnet nécessitent un RPC valide dans `.env`.
- Tous les tests ont été validés localement avant rendu.

---

## Disclaimer

Tout ce code est volontairement vulnérable et destiné à des fins pédagogiques.  
**Ne jamais utiliser en production.**


