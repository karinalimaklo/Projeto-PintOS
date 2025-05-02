# Projeto PintOS - Infraestrutura de Software (2024.2)
Esse projeto consistiu na implementação de funcionalidades do sistema operacional PintOS.

## Objetivos
[x] Alarm Clock
[x] Advanced Scheduler - Multi-Level Feedback Queue (mlfqs)

## Testes
| #  | Teste                        | Funcionando |
|----|------------------------------|-------------|
| 1  | `alarm-single`               | ✅          |
| 2  | `alarm-multiple`             | ✅          |
| 3  | `alarm-simultaneous`         | ✅          |
| 4  | `alarm-priority` *           | ✅          |
| 5  | `alarm-zero`                 | ✅          |
| 6  | `alarm-negative`             | ✅          |
| 7  | `priority-change` *          | ✅          |
| 8  | `priority-donate-one` *      | ❌          |
| 9  | `priority-donate-multiple` * | ❌          |
| 10 | `priority-donate-multiple2` *| ❌          |
| 11 | `priority-donate-nest` *     |	❌          |
| 12 | `priority-donate-sema` *     | ❌          |
| 13 | `priority-donate-lower` *	  | ❌          |
| 14 | `priority-fifo` *	          | ✅          |
| 15 | `priority-preempt` *         | ✅          |
| 16 | `priority-sema` *            | ❌          |
| 17 | `priority-condvar` *         |	❌          |
| 18 | `priority-donate-chain` *    | ❌          |
| 19 | `mlfqs-load-1` 	            | ✅          |
| 20 | `mlfqs-load-60`	            | ✅          |
| 21 | `mlfqs-load-avg`             | ✅          |
| 22 | `mlfqs-recent-1`             |	✅          |
| 23 | `mlfqs-fair-2`               | ✅          |
| 24 | `mlfqs-fair-20`  	          | ✅          |
| 25 | `mlfqs-nice-2` 	            | ✅          |
| 26 | `mlfqs-nice-10`  	          | ✅          |
| 27 | `mlfqs-block` 	              | ✅          |
