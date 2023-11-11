# d1609_backpack LINK TO PURCHASE IT FOR FREE / LINK PARA ADQUIRIRLO GRATIS

<b>https://d1609-scripts-shop.tebex.io/package/5990624<b>

# d1609_backpack ENGLISH

This resource was created as a free script for backpacks using ox_inventory

<b>Features:</b>
- 0.0 ms Usage
- Perisistent backpack prop added to back when in inventory
- Customizable item name and storage parameters
- Compatibility for ox_core, ESX, QBCore, whatever else running ox_inventory

## Installation

- Download this script
- Add backpack to inventory as it is in "Extra Information" below
- Add backpack image to inventory images (found in `d1609_backpack/Inventory Images/backpack.png`)
- Put script in your `resources` directory
- ensure `d1609_backpack` *after* `ox_lib` but *before* `ox_inventory`

# Dependencies
 - ox_inventory

## Extra Information
Item to add to `ox_inventory/data/items.lua`
```
	['backpack'] = {
		label = 'Backpack',
		weight = 220,
		stack = false,
		consume = 0,
		client = {
			export = 'D1609_backpack.openBackpack'
		}
	},
```

# d1609_backpack ESPAÑOL

Este resource fue creado como un script gratuito para mochilas usando ox_inventory

<b>Características:</b>
- 0,0 ms Uso
- Un accesorio de mochila persistente a la espalda cuando está en el inventario.
- Nombre del artículo personalizable y parámetros de almacenamiento.
- Compatibilidad con ox_core, ESX, QBCore y cualquier otra cosa que ejecute ox_inventory

## Instalación

- Descarga este resource
- Agregue la mochila al inventario tal como aparece en "Información extra" a continuación
- Agregar imagen de mochila a las imágenes de inventario (que se encuentran en `d1609_backpack/Inventory Images/backpack.png`)
- Coloque el script en su directorio `resources`
- Asegúrese de que `d1609_backpack` se ejecute *después* de `ox_lib` y de `ox_inventory`

# Dependencias
  - ox_inventory

## Información extra
Elemento para agregar a `ox_inventory/data/items.lua`
```
	['backpack'] = {
		label = 'Mochila',
		weight = 220,
		stack = false,
		consume = 0,
		client = {
			export = 'D1609_backpack.openBackpack'
		}
	},
```

