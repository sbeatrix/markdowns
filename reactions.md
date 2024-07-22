| **Name**                                  | **Reaction**                 | **Rate Law**                                                                                      |
|-------------------------------------------|------------------------------|---------------------------------------------------------------------------------------------------|
| Cdc20 promoter activation                 | p_off_CDC20 → p_on_CDC20     | $k_{on_{CDC20}}\cdot p_{off_{CDC20}}$                                                               |
| Cdc20 promoter inactivation               | p_on_CDC20 → p_off_CDC20     | $k_{off_{CDC20}}\cdot p_{on_{CDC20}}$                                                               |
| Cdc20 synthesis                           | p_on_CDC20 → C + p_on_CDC20  | $ksyn_{CDC20}\cdot p_{on_{CDC20}}$                                                                   |
| X (Mps1/CycB) promoter activation                  | p_off_X → p_on_X             | $k_{on\_X}\cdot p_{off\_X}$                                                                       |
| X (Mps1/CycB) promoter inactivation                | p_on_X → p_off_X             | $k_{off\_X}\cdot p_{on\_X}$                                                                       |
| X (Mps1/CycB) synthesis                            | p_on_X → X + p_on_X          | $ksyn_{X}\cdot p_{on\_X}$                                                                         |
| Cdc20 background degradation              | C → Ø                        | $kdegBG\cdot C$                                                                                   |
| X (Mps1/CycB) degradation                      | X → Ø                     | $kdeg_{X} \cdot X\cdot AC$                                                                    |
| X (Mps1/CycB) background degradation           | X → Ø                     | $kdegBG_{X}\cdot X$                                                                           |
| $Mad2_{i}$ (checkpoint components) activation      | $Mad2_{i} → Mad2_{a}$                       | $\frac{kact\cdot X \cdot Mad2_{i}\cdot k_{nuk}\cdot nUK}{(J+Mad2_{i})(J_n+nUK)}$                               |
| $Mad2_{a}$ (active checkpoint components) inactivation | $Mad2_{a} → Mad2_{i}$                   | $kinact\cdot \frac{Mad2_{a}}{J+Mad2_{a}}$                                                                   |
| MCC (checkpoint core complex) formation   | $Mad2_a$ + C → MC                  | $kassMC\cdot M\cdot C$                                                                            |
| MCC dissociation                          | MC → $Mad2_a$ + C                  | $kdissMC\cdot MC$                                                                                 |
| APC/Cdc20 (AC) formation                  | A + C → AC                   | $kassAC\cdot AC$                                                                                  |
| APC/Cdc20 dissociation                    | AC → A + C                   | $kdissAC\cdot AC$                                                                                 |
| APCinhib (ACMC) formation                 | MC + AC → ACMC               | $kassACMC\cdot MC\cdot AC$                                                                        |
| APCinhib dissociation                     | ACMC → MC + AC               | $kdissACMC\cdot ACMC$                                                                             |
| APCinhib degradation                      | ACMC → A + C + M             | $kdeg\cdot ACMC$                                                                                  |
| MCC background degradation                | MC → M                       | $kdegBG\cdot MC$                                                                                  |
| APCCdc20 background degradation           | AC → A                       | $kdegBG\cdot AC$                                                                                  |
| APCinhib background degradation           | ACMC → A + M                 | $kdegBG\cdot ACMC$                                                                                |
| Kinetochore attachment dynamics           | nUK → Ø                      | $nUK\cdot knUKatt$                                                                                |


