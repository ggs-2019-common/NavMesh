# NavMesh
**Utilisation de Navmesh Surface et Agents Type**
 - Créer Plusieurs agents types.
 - Aller dans le GO Navmesh -> Surfaces
 - Rajouter un GO avec le composant NavMeshSurface
 - Sélectionner l'agent type et les layers
 - Bake cette surface.

**Les pièges**
Attention à ne pas bake le navigation global, il peut servir à tester un bake mais ne doit pas être présent dans le rendu final, il ne doit y avoir que des surfaces, pour les types d'agents concernés.
