Powerful Placeholder
====================

	Описание:
	---------

		-Добавляет поддержку placeholder для полей ввода в старых браузерах.
		-Фиксит "проблему" браузеров Webkit(Chrome и т.д.) с нестиранием подсказки при получении фокуса.

	Использование:
	--------------

		$(document).ready(function(){
			$.Placeholder.init({ color : "#aaa" });
		});