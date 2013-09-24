=================================
Documentation TYPO3 pour éditeurs
=================================

La documentation se trouve dans le répertoire ``Documentation/``.

Vous pouvez facilement intégrer cette documentation dans TYPO3 en utilisant
l'extension `sphinx <http://typo3.org/extensions/repository/view/sphinx>`_.

Pour se faire, commencez par faire un clône de ce dépôt Git dans votre ``fileadmin/``,
par exemple sous ``fileadmin/Documentation-Editeurs/``.

Créez ensuite un fichier texte ``typo3conf/sphinx-projects.json``::

	[
		{
			"name": "Editeurs FR",
			"description": "Adaptation française libre de la documentation pour les éditeurs du CMS TYPO3",
			"group": "Personnel",
			"key": "personnel.editeurs",
			"directory": "fileadmin/Documentation-Editeurs/Documentation/"
		}
	]

Ouvrez le module Backend Aide > Documentation Sphinx et travaillez directement sur
le document grâce au mode "Interactif".
