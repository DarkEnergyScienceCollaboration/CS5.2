#  Verify that existing input variability models are sufficient

Summary -- Variability in Twinkles 1 includes strong lensing and supernovae. Variability models within CatSim
can support the complexity required by these sources but will require extending to incorporate a diverse set
of light curves. The Twinkles team will provide their own models to augment CatSim but these custom models
will need to be supported by the CatSim API.

## Key Tasks
* Key Task CS5.2.1 ( 09/16 ): Gather variability models.
* Key Task CS5.2.2 ( 09/16 ): Verify completeness of the variability models. This will require a meeting with
the interested parties.
* Key Task CS5.2.3 ( 09/16 ): Extend CatSim where needed to deal with any new variability models.

### Suggested organization
Repositories are available per deliverable.  Each key task has a subdirectory.
We have a `source` directory in each key task area for any supporting
code that goes with an effort.  There will also be a `doc` directory to hold documents in markdown,
latex, or binary formats.  The idea is to version everything and give us a good way to diff things.

Each deliverable is slightly different, so these repositories should grow to support the different need.

Please feel free to use github issues on each repository to organize work.
