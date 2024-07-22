| **Name**                                  | **Reaction**                 | **Rate Law**                                                                                      |
|-------------------------------------------|------------------------------|---------------------------------------------------------------------------------------------------|
| Cdc20 promoter activation                 | $p_{off_{CDC20}} \rightarrow p_{on_{CDC20}}$     | $k_{on_{CDC20}}\cdot p_{off_{CDC20}}$                                                               |
| Cdc20 promoter inactivation               | $p_{on_{CDC20}} \rightarrow p_{off_{CDC20}}$     | $k_{off_{CDC20}}\cdot p_{on_{CDC20}}$                                                               |
| Cdc20 synthesis                           | $p_{on_{CDC20}} \rightarrow C + p_{on_{CDC20}}$  | $ksyn_{CDC20}\cdot p_{on_{CDC20}}$                                                                   |
| X (Mps1/CycB) promoter activation                  | $p_{off\_X} \rightarrow p_{on\_X}$             | $k_{on\_X}\cdot p_{off\_X}$                                                                       |
| X (Mps1/CycB) promoter inactivation                | $p_{on\_X} \rightarrow p_{off\_X}$             | $k_{off\_X}\cdot p_{on\_X}$                                                                       |
| X (Mps1/CycB) synthesis                            | $p_{on\_X} \rightarrow X + p_{on\_X}$          | $ksyn\_{X}\cdot p_{on\_X}$                                                                         |
| Cdc20 background degradation              | $C \rightarrow \varnothing$                        | $kdegBG\cdot C$                                                                                   |
| X (Mps1/CycB) degradation                      | $X \rightarrow \varnothing$                     | $kdeg\_{X} \cdot X\cdot AC$                                                                    |
| X (Mps1/CycB) background degradation           | $X \rightarrow \varnothing$                     | $kdegBG\_{X}\cdot X$                                                                           |
| $Mad2_{i}$ (checkpoint components) activation      | $Mad2_{i} \rightarrow Mad2_{a}$                       | $\frac{kact\cdot X \cdot Mad2_{i}\cdot k_{nuk}\cdot nUK}{(J+Mad2_{i})(J_n+nUK)}$                               |
| $Mad2_{a}$ (active checkpoint components) inactivation | $Mad2_{a} \rightarrow Mad2_{i}$                   | $kinact\cdot \frac{Mad2_{a}}{J+Mad2_{a}}$                                                                   |
| MCC (checkpoint core complex) formation   | $Mad2_{a} + C \rightarrow MC$                  | $kassMC\cdot M\cdot C$                                                                            |
| MCC dissociation                          | $MC \rightarrow Mad2_{a} + C$                  | $kdissMC\cdot MC$                                                                                 |
| APC/Cdc20 (AC) formation                  | $A + C \rightarrow AC$                   | $kassAC\cdot AC$                                                                                  |
| APC/Cdc20 dissociation                    | $AC \rightarrow A + C$                   | $kdissAC\cdot AC$                                                                                 |
| APCinhib (ACMC) formation                 | $MC + AC \rightarrow ACMC$               | $kassACMC\cdot MC\cdot AC$                                                                        |
| APCinhib dissociation                     | $ACMC \rightarrow MC + AC$               | $kdissACMC\cdot ACMC$                                                                             |
| APCinhib degradation                      | $ACMC \rightarrow A + C + M$             | $kdeg\cdot ACMC$                                                                                  |
| MCC background degradation                | $MC \rightarrow M$                       | $kdegBG\cdot MC$                                                                                  |
| APCCdc20 background degradation           | $AC \rightarrow A$                       | $kdegBG\cdot AC$                                                                                  |
| APCinhib background degradation           | $ACMC \rightarrow A + M$                 | $kdegBG\cdot ACMC$                                                                                |
| Kinetochore attachment dynamics           | $nUK \rightarrow \varnothing$            | $nUK\cdot knUKatt$    
