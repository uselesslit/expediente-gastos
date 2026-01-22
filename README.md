# 📊 EXPEDIENTE DE GASTOS - SERVICIOS DE ALIMENTACIÓN

## 📁 Archivos del Sistema

| Archivo | Descripción | Uso |
|---------|-------------|-----|
| 📄 [expediente-gastos.md](expediente-gastos.md) | Expediente completo con formato elegante | Presentaciones, reportes, visualización |
| 📊 [gastos-detalle.csv](gastos-detalle.csv) | Datos estructurados para análisis | Excel, Google Sheets, análisis |

## 🎯 ¿Cómo usar este sistema?

### 📱 Para Presentaciones
- Abre `expediente-gastos.md` en GitHub
- Se ve profesional y ordenado
- Exporta a PDF desde el navegador

### 📊 Para Análisis en Excel
- Descarga `gastos-detalle.csv`
- Abre en Excel/Google Sheets
- Crea gráficos y tablas dinámicas
- **Importante:** Para calcular totales, suma la columna `Total_a_Contar` (evita duplicación de facturas con múltiples items)

### 🔄 Para Actualizar
- Edita directamente en GitHub
- Los cambios se ven en tiempo real
- Mantén ambos archivos sincronizados

## 📈 Resumen Actual

**Fecha:** Lunes 05 Enero 2026
- **Ingresos:** S/ 3,000.00
- **Gastos:** S/ 3,045.50  
- **Balance:** -S/ 45.50

## 📝 Nota sobre el CSV

El archivo CSV está estructurado para análisis detallado:
- Cada fila representa un producto individual
- Para facturas con múltiples items, solo la primera fila tiene `Total_a_Contar`
- Esto evita duplicación al sumar totales
- Para análisis por item, usa `Subtotal_Item`
- Para totales generales, suma `Total_a_Contar`

---
*Sistema creado para control eficiente de gastos de servicios de alimentación*