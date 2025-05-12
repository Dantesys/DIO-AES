# DIO AErquitetura e Serviços

O módulo trata dos principais componentes arquitetônicos da plataforma de nuvem Microsoft Azure, oferecendo uma visão geral de como seus serviços são organizados, distribuídos e gerenciados.

1. Regiões e Zonas de Disponibilidade:

O Azure está presente em mais de 60 regiões que abrangem mais de 140 países.

Regiões são conjuntos de datacenters localizados próximos entre si, permitindo baixa latência e conformidade com a residência de dados.

Zonas de disponibilidade são datacenters fisicamente separados dentro da mesma região, oferecendo maior resiliência e proteção contra falhas.

Pares de regiões são duas regiões emparelhadas para permitir recuperação de desastres, com atualizações aplicadas sequencialmente para reduzir o impacto.

2. Regiões Soberanas:

Incluem ambientes separados como o Azure Governamental, criado para entidades governamentais dos EUA, com acesso restrito e conformidade rigorosa.

3. Recursos e Grupos de Recursos:

Recursos são elementos como máquinas virtuais, redes e armazenamento.

Os grupos de recursos organizam os recursos de maneira lógica para facilitar o gerenciamento, podendo conter recursos de diferentes regiões.

4. Assinaturas do Azure:

Representam uma forma de acesso autenticado e autorizado aos recursos da nuvem.

Servem como unidades de cobrança e controle de acesso individualizado.

5. Grupos de Gerenciamento:

São utilizados para gerenciar múltiplas assinaturas em uma estrutura hierárquica, permitindo aplicar políticas de maneira centralizada.

6. Contas do Azure:

O Azure oferece contas gratuitas, inclusive para estudantes, com acesso a recursos limitados e área de aprendizado prática através do Microsoft Learn.
