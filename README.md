# Aim-for-the-cam
## Apenas GTASA – 32 bits 2.0 -
Dentro do mangle _ZN4CCam17Process_AimWeaponERK7CVectorfff no offset 0x3C6D50 {linha + 218 em ASSEMBLY} faz a verificacao da condicional jump, Cortando esse jump pra 1 no float* muda esse fluxo fazendo a mira nao restaurar a mira ao mirar 
Resumindo a mira fica travada/estavel, apontando exatamente para onde a câmera estava mirando sem o evento de reset da mira 
