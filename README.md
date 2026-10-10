# Additive Manufacturing in Modern Industry

A B.Tech Mechatronics seminar report on how additive manufacturing (3D printing) is changing the way parts are designed and made. It reviews five recent research papers, compares the main print processes, and looks closely at selective laser sintering (SLS).

Author: Anand S. Guide: Mr. Syam K, Assistant Professor, Department of Mechatronics.
Nirmala College of Engineering, Technology and Management (NiCETM), Chalakudy, affiliated to the APJ Abdul Kalam Technological University. December 2023.

<!-- Add your links here -->
**Portfolio:** <your portfolio link>  
**Full report (PDF):** see `report/`

## What the report covers

| Chapter | Topic |
| --- | --- |
| 1 | Introduction and background |
| 2 | Literature survey of five papers (2022 to 2023) |
| 3 | How additive differs from subtractive manufacturing |
| 4 | Rapid prototyping |
| 5 | Software used: AutoCAD, SolidWorks, Fusion 360, TinkerCAD, Blender, OpenSCAD |
| 6 | Types of AM process: FDM, SLA, SLS |
| 7 to 10 | Selective laser sintering, sintering, materials and how SLS works |
| 12 | Advantages and disadvantages |
| 13 | Conclusion |

## Key findings

- **Heat exchangers:** laser powder bed fusion suits complex heat exchangers, but leak-proof thin walls and surface quality need more research (Careri et al., 2023).
- **Sustainability:** AM raised costs but gave environmental benefits in an industrial machinery case, and cut both cost and environmental impact in an aeronautical case (Gonçalves et al., 2023).
- **Contactless supports:** 66% less post-processing time, with problems at angles above 10° (Paggi et al., 2022).
- **Thermal monitoring:** a method that captures both timing and location of heat in extrusion printing (Colosimo et al., 2023).
- **Lean and AM:** digital tools and simulation-driven design for AM reduce waste (Lakshmanan et al., 2023).

## AM versus subtractive manufacturing

| Point | Additive | Subtractive |
| --- | --- | --- |
| Process | Builds layer by layer | Removes material from a block |
| Design freedom | Complex and internal geometry | Limited by tools |
| Material use | Adds only where needed | Significant waste |
| Tooling | Minimal | Cutting tools, fixtures, molds |
| Best for | Custom, small batch, complex parts | Simpler shapes, high volume |

## Print processes

- **FDM:** melted thermoplastic (ABS, PLA) extruded layer by layer.
- **SLA:** UV laser cures liquid resin; high resolution and smooth surfaces.
- **SLS:** laser sinters powder (polymers, metals, ceramics); the loose powder supports the part, so no support structures are needed.

## Repository layout

```
.
├── report/        Full seminar report (PDF)
├── figures/       Figures and images from the report
├── slides/        Seminar presentation, if any
├── LICENSE
└── README.md
```

## License

Released under the MIT License. See [LICENSE](LICENSE). Figures that come from the cited papers belong to their original authors.

## References

1. Careri et al. (2023). Additive manufacturing of heat exchangers in aerospace applications.
2. Gonçalves et al. (2023). Environmental and economic sustainability impacts of metal additive manufacturing.
3. Paggi et al. (2022). Implementation of contactless supports for industrially relevant additively manufactured parts in metal.
4. Colosimo et al. (2023). Spatio-temporal analysis of thermal profiles in extrusion based additive manufacturing.
5. Lakshmanan et al. (2023). The convergence of lean management and additive manufacturing: case of manufacturing industries.
6. ISO/ASTM 52900:2021. Additive manufacturing, general principles.
