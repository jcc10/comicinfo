# ComicInfo.xml [Batch Archive Proposal]

## Proposal
This branch is meant to contain a copy of the modifications that would be required to add support for tagging when a archive has a batch of comics within it.

### What is this meant to fix
There are times when a CBZ may contain more than one issue from a comic. This is meant to allow signifying that a item may cover multiple sequential issue places.

Situations this may be needed:

* Comic is serialised weekly and at the end of every quarter a paperback is released grouping all of them together.
* Batch archival of comics.

## What is it?

The `ComicInfo.xml` file originates from the ComicRack application, which is not developed anymore. The `ComicInfo.xml` however is used by a variety of applications.

There is, however, no governance about the file format, until now!

This project aims at:
1. documenting the existing versions of the schema, with the accepted usage of each field
2. centralizing evolutions of the schema

## Where can I find the schemas?

Schemas are available in [schema](./schema), each version in a separate directory.

Current drafts are available in [drafts](./drafts), each version in a separate directory.

## Who's behind this?

Supporters of this initiative include:
- [Komga](https://komga.org)
- [Kavita](https://www.kavitareader.com/)
- [Codex](https://github.com/ajslater/codex)
