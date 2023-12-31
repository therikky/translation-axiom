# Искажения
Инструмент искажений использует концепцию, называемую «Domain Distortion» с симплексным шумом, чтобы исказить заданную область. На практике это делает области более неровными. Это может помочь сделать плоские области более глубокими и текстурными или использоваться для добавления неровностей и вырезов в более изысканный ландшафт. Он делает это внутри пути мазка кисти, который можно определить в настройках кисти.

Искажение можно настроить дополнительно, чтобы точно настроить, как вы хотите исказить ландшафт. Масштаб задает масштаб симплексного шума, используемого для искажения домена. Это может быть настроено на большие размеры, если масштаб недостаточно велик. Его также можно настроить с помощью начального числа для использования разных или случайных начальных значений.

Расстояние искажения увеличивает диапазон, в котором шум искажается. Расстояние 2 означает среднее расстояние в 2 блока от целевой позиции. Из-за того, что шум является непрерывным, диапазон может быть установлен на неполные числа, чтобы точно настроить диапазон, иногда в результате появляются более крупные вмятины или неровности. Большое расстояние заставит его выглядеть более «суровым». Эти расстояния можно разделить по осям, нажав кнопку * Разделить ось.

Параметр «Сглаженные края» смешивает края шума с существующим ландшафтом, чтобы избежать появления неровных краев и резких контрастов между искаженными областями.
