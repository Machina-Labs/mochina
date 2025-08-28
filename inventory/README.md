# Inventory Tracking System

This directory contains YAML files for tracking coffee equipment and supplies at both Machina Labs locations.

## File Structure

- **[prairie-kitchen.yml](./prairie-kitchen.yml)** - Prairie location inventory
- **[owensmouth-kitchen.yml](./owensmouth-kitchen.yml)** - Owensmouth location inventory
- **[supplies-tracking.yml](./supplies-tracking.yml)** - Consumable supplies tracking
- **[maintenance-schedule.yml](./maintenance-schedule.yml)** - Equipment maintenance tracking

## How to Use

### Equipment Status Codes
- **excellent** - Like new, no issues
- **good** - Minor wear, fully functional
- **fair** - Some wear, may need attention soon
- **poor** - Significant wear, needs replacement/repair
- **broken** - Not functional, immediate attention required

### Maintenance Status
- **current** - Up to date with maintenance
- **due** - Maintenance needed soon
- **overdue** - Maintenance past due date
- **scheduled** - Maintenance appointment scheduled

### Supply Levels
- **full** - Well stocked
- **adequate** - Sufficient for normal operations
- **low** - Need to reorder soon
- **critical** - Immediate reorder required
- **out** - Out of stock

## Updating Inventory

1. **Regular Checks** - Weekly equipment status review
2. **After Issues** - Update status when problems occur
3. **Post-Maintenance** - Update after cleaning/repairs
4. **Supply Monitoring** - Check consumables weekly

## Replacement Planning

### Equipment Lifecycle
- **Coffee Machines** - 5-7 years typical lifespan
- **Grinders** - 3-5 years with heavy use
- **Accessories** - 1-2 years depending on item

### Budget Planning
Use this data to:
- Forecast replacement needs
- Plan maintenance schedules
- Track warranty periods
- Monitor usage patterns

## Reporting Issues

When equipment status changes to "fair" or worse:
1. Update the YAML file
2. Document the issue in notes
3. Research repair/replacement options
4. Schedule maintenance if needed
5. Consider temporary alternatives

---

*Keep this inventory updated to ensure smooth coffee operations and prevent unexpected equipment failures.*
