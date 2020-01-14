## API Report File for "@edtr-io/plugin-spoiler"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { EditorPlugin } from '@edtr-io/plugin';
import { EditorPluginProps } from '@edtr-io/plugin';

// @public (undocumented)
export function createSpoilerPlugin({ theme }?: {
    theme?: Partial<SpoilerConfig['theme']>;
}): EditorPlugin<SpoilerState, SpoilerConfig>;

// @public (undocumented)
export interface SpoilerConfig {
    // (undocumented)
    theme: {
        color: string;
    };
}

// @public (undocumented)
export type SpoilerProps = EditorPluginProps<SpoilerState, SpoilerConfig>;

// @public (undocumented)
export type SpoilerState = typeof spoilerState;

// @public (undocumented)
export const spoilerState: import("@edtr-io/internal__plugin-state").StateType<import("@edtr-io/internal__plugin-state").StateTypesSerializedType<{
    title: import("@edtr-io/internal__plugin-state").StateType<string, string, {
        value: string;
        get(): string;
        set(value: string | ((currentValue: string) => string)): void;
    }>;
    content: import("@edtr-io/internal__plugin-state").StateType<{
        plugin: "rows";
        state?: unknown;
    }, string, {
        get(): string;
        id: string;
        render: (props?: import("@edtr-io/internal__plugin-state").PluginProps | undefined) => import("react").ReactNode;
        replace: (plugin?: "rows" | undefined, state?: unknown) => void;
    }>;
}>, import("@edtr-io/internal__plugin-state").StateTypesValueType<{
    title: import("@edtr-io/internal__plugin-state").StateType<string, string, {
        value: string;
        get(): string;
        set(value: string | ((currentValue: string) => string)): void;
    }>;
    content: import("@edtr-io/internal__plugin-state").StateType<{
        plugin: "rows";
        state?: unknown;
    }, string, {
        get(): string;
        id: string;
        render: (props?: import("@edtr-io/internal__plugin-state").PluginProps | undefined) => import("react").ReactNode;
        replace: (plugin?: "rows" | undefined, state?: unknown) => void;
    }>;
}>, import("@edtr-io/internal__plugin-state").StateTypesReturnType<{
    title: import("@edtr-io/internal__plugin-state").StateType<string, string, {
        value: string;
        get(): string;
        set(value: string | ((currentValue: string) => string)): void;
    }>;
    content: import("@edtr-io/internal__plugin-state").StateType<{
        plugin: "rows";
        state?: unknown;
    }, string, {
        get(): string;
        id: string;
        render: (props?: import("@edtr-io/internal__plugin-state").PluginProps | undefined) => import("react").ReactNode;
        replace: (plugin?: "rows" | undefined, state?: unknown) => void;
    }>;
}>>;


// (No @packageDocumentation comment for this package)

```